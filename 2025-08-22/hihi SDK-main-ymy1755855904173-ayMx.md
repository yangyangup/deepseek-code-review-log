diff --git a/code-review-sdk/src/main/java/com/hihi/sdk/CodeReview.java b/code-review-sdk/src/main/java/com/hihi/sdk/CodeReview.java
index 082478c..5f2cd01 100644
--- a/code-review-sdk/src/main/java/com/hihi/sdk/CodeReview.java
+++ b/code-review-sdk/src/main/java/com/hihi/sdk/CodeReview.java
@@ -1,22 +1,16 @@
 package com.hihi.sdk;
 
-import com.fasterxml.jackson.databind.annotation.JsonTypeIdResolver;
-import com.hihi.sdk.domain.service.impl.OpenAiCodeReviewService;
-
 
+import com.hihi.sdk.domain.service.impl.OpenAiCodeReviewService;
 import com.hihi.sdk.infrastructure.deepseek.IDeepseekAI;
 import com.hihi.sdk.infrastructure.deepseek.impl.DeepseekAI;
-import com.hihi.sdk.infrastructure.git.GitCommand;
+import com.hihi.sdk.infrastructure.git.dto.GitCommandInfo;
+import com.hihi.sdk.infrastructure.git.impl.GitCommand;
 import com.hihi.sdk.infrastructure.weixin.WeiXin;
-
-
 import org.slf4j.Logger;
 import org.slf4j.LoggerFactory;
 import org.springframework.boot.SpringBootConfiguratio
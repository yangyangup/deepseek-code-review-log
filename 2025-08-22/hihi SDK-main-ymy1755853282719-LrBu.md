diff --git a/code-review-test/data/log/log_error.log b/code-review-test/data/log/log_error.log
index 3b5282c..81a698b 100644
--- a/code-review-test/data/log/log_error.log
+++ b/code-review-test/data/log/log_error.log
@@ -1,313 +1,32 @@
-25-07-31.15:43:06.444 [main            ] WARN  GenericWebApplicationContext - Exception encountered during context initialization - cancelling refresh attempt: org.springframework.beans.factory.UnsatisfiedDependencyException: Error creating bean with name 'com.hihi.sdk.infrastructure.config.SdkAutoConfiguration': Unsatisfied dependency expressed through constructor parameter 0; nested exception is org.springframework.boot.context.properties.ConfigurationPropertiesBindException: Error creating bean with name 'hihi.codeReview.sdk-com.hihi.sdk.infrastructure.config.SdkProperties': Could not bind properties to 'SdkProperties' : prefix=hihi.codeReview.sdk, ignoreInvalidFields=false, ignoreUnknownFields=true; nested exception is org.springframework.boot.conte
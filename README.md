# How_to_use_AWS_Cognito_Android_SDK_with_Kotlin

概要
AWS Cognito認証機能を利用して、既存のAWSユーザープールを使用し
Android向けのユーザーログイン機能をKotlinで実装する簡単な方法。

※今回はAWS Amplifyを使用しない方法での説明
2023年1月現在でAWS公式はAmplifyを今後の主流として推奨しているようなので、
aws-android-sdk(旧型)ではなくAmplifyを使用する実装の方が望ましいかもしれない。
単純に認証機能を実装したいだけであれば、aws-android-sdkで十分なのかもしれない。

参考　AWS公式
https://aws.amazon.com/jp/blogs/mobile/using-android-sdk-with-amazon-cognito-your-user-pools/

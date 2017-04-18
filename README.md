PythonConsole is a command-line application in a Visual Studio solution. It demonstrates how to get an authentication token and how to use the Text Translation API to translate text from one language to text in another language.

The sample application only offers translation between 5 languages, but the service offers translations for 50+ languages.

This sample requires a subscription with Microsoft Translator Text Translation API, which is part of Microsoft Azure Cognitive Services. Visit the [Text Translation API documentation page](http://docs.microsofttranslator.com/text-translate.html) to get started.

After subscribing to the Text Translation API, visit the Azure developer portal to retrieve your subscription secret key. Paste this client secret in the sample application code (in `MainWindow.xaml.cs`) and you are ready to go.


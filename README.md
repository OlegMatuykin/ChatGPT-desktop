# ChatGPT for desktop

ChatGPT for desktop is the same ChatGPT but for Windows as desktop application

ChatGPT windows is an AI chatbot that uses natural language processing to create humanlike conversational dialogue. 

1.   The language model can 
     - respond to questions and compose various written content
     - it can write articles
     - create social media posts
     - write essays, code and emails.
     
2.   Perks of having ChatGPT windows App:
     - An icon on your quick access spots
     - One-click launch
     - No need for an open browser tab

ChatGPT desktop works on Windos 7, Widows 8, Windows 10, Windows 11.

What are you waiting for? Hit Download and open up ChatGPT App on your Windows platform Desktop or Laptop.

## Installation

To get ChatGPT desktop for Windows, you can [Download ChatGPT desktop installer]().

Or you can check the [releases]() page.

## Usage

Run the "ChatGPT.desktop.install.exe" and follow installation instructions.

## For professionals

3.   You can build whole application from source code. For that you will need:
     - Visual studio 2019 with support to build .NET Framework 4.6
     - If you would like to create such installer as in release, you will need NSIS 2.5.1.

Run Developer Command Prompt for VS 2019

Execute commands in this prompt:

```
msbuild "ChatGPT desktop\ChatGPT desktop.sln" /p:Configuration=Release /p:SelfContained=True /p:PackageAsSingleFile=true /t:Publish /p:PublishDir=Publish

makensis installer_script.nsi
```


## Contributing

Pull requests are welcome. For major changes, please open an issue first
to discuss what you would like to change.

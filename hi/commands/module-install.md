# module:install
मोड्यूल या मोड्यूलो को अनुप्रयोग में स्थापित करें

**Usage:**
```
drupal module:install [arguments] [options]
moi
```

## Available options
Option | Details
-------|-------------
--latest | डिफ़ॉल्ट नवीनतम संस्करण डाउनलोड करने के लिए
--composer | Uninstalls the module using Composer
--help | Display this help message
--quiet | Do not output any message
--verbose | Increase the verbosity of messages: 1 for normal output, 2 for more verbose output and 3 for debug
--version | Display this application version
--ansi | Force ANSI output
--no-ansi | Disable ANSI output
--no-interaction | Do not ask any interactive question
--env | The Environment name
--root | Define the Drupal root to be used in command execution
--debug | Switches on debug mode
--learning | Generate a verbose code output
--generate-chain | Shows command options and arguments as yaml output to be used in chain command
--generate-inline | Shows command options and arguments as inline command
--generate-doc | Shows command options and arguments as markdown
--target | Site name you want to interact with (for local or remote sites)
--uri | URI of the Drupal site to use (for multi-site environments or when running on an alternate port)
--yes | Skip confirmation and proceed

## Available arguments
Argument | Details
---------|-------------
command | The command to execute
module | मॉड्यूल या मॉड्यूलस सक्षम होने के लिए एक स्पेस से सेपरेट किया जाना चाहिए

## Examples
* Install module specifying the module name
```
drupal module:install  modulename
```

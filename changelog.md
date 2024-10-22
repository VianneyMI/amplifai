# Release Notes

## 0.0.1 - 2024/10/17 - Initial release

### New Features

* Basic Structure of the framework
* `Amplifier` class allows to transforms raw text into pydantic objects

## 0.0.2 - 2024/10/21 - Second release

### Fixes

* Fixed dependency to deprecated module that was breaking previous release

## 0.0.3 - 2024/10/22 - Third release

### Refactors

* Converted `llm`attribute into a an `Amplifier` class type parameter
* Improved typing of `denoise`methods
* Added a private function to retrieve the `ChatModel`pass as a type parameter.

### Packaging

* Removed dependency on `langchain_openai` and `langchain_mistralai` packages.

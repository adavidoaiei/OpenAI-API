# Semantic Kernel OpenAI Summarizer

This is a sample C# console application demonstrating how to use the Microsoft Semantic Kernel with the OpenAI API to summarize text.

## Description

The application uses the `text-davinci-003` model to create a five-word "TLDR" (Too Long; Didn't Read) summary of Asimov's Three Laws of Robotics.

## Prerequisites

*   .NET SDK (e.g., .NET 6.0 or later)
*   An active OpenAI API Key

## How to Run

1.  **Set up your API Key**

    For security, the application is configured to read your OpenAI API key from an environment variable. Before running the application, you need to set the `OPENAI_API_KEY` environment variable.

    **On Windows (PowerShell):**
    ```powershell
    $env:OPENAI_API_KEY="your-secret-api-key"
    ```

    **On macOS/Linux (bash/zsh):**
    ```bash
    export OPENAI_API_KEY="your-secret-api-key"
    ```

2.  **Run the application**

    Navigate to the `OpenAPI` project directory and use the `dotnet run` command:
    ```bash
    cd OpenAPI
    dotnet run
    ```

## Expected Output

```
Protect humans, follow orders, survive.
```
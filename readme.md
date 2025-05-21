
# Go Gemini - Customer Retention Idea Generator

This is a Go program that uses the Google Generative AI Go SDK to interact with the Gemini model. The program generates ideas for customer retention strategies based on a given prompt.

## Features

- Connects to the Gemini model using the Google Generative AI Go SDK.
- Generates structured ideas for customer retention strategies.
- Outputs the generated content in a readable format.

## Prerequisites

- Go 1.18 or later
- A valid API key for Google Generative AI
- A `.env` file with the following content:
  ```
  API_KEY=your_api_key_here
  ```

## Installation

1. Clone the repository:
   ```bash
   git clone <repository-url>
   cd go-gemini
   ```

2. Install dependencies:
   ```bash
   go mod tidy
   ```

3. Create a `.env` file in the root directory and add your API key:
   ```
   API_KEY=your_api_key_here
   ```

## Usage

Run the program with the following command:
```bash
go run main.go
```

The program will generate ideas for customer retention strategies and print the results to the console.

### Example Output

The program generates ideas in the following format:
```
- アイデア: [Generated idea]
- 期待される効果: [Expected effect]
```

## Project Structure

```
.env          # Environment variables (API key)
go.mod        # Go module dependencies
go.sum        # Dependency checksums
main.go       # Main program logic
```

## Dependencies

- [Google Generative AI Go SDK](https://github.com/google/generative-ai-go)
- [godotenv](https://github.com/joho/godotenv)

## Error Handling

- If the `.env` file is missing or the API key is invalid, the program will terminate with an error message.
- Ensure the API key is correctly set in the `.env` file.

## License

This project is licensed under the MIT License. See the LICENSE file for details.

# Wordle: Guess the Hidden Word

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/d997b079-6c7f-4222-b0e4-05b3e5f5f032" />

The rules are very simple: You have to guess the hidden word (from 5 letters) in 6 tries. To get started, just type any word on the first line. If the letter is guessed correctly and is in the correct place, it will be highlighted in green, if the letter is in the word, but in the wrong place - in yellow, and if the letter is not in the word, it will turn pink.

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/6df520f9-5e2c-40d6-b4f6-4b145123cd53" />

## Different Languages
There is a choice of two languages: **English** and **Russian**.

## Building

### Prerequisites
- [Maven](https://maven.apache.org/download.cgi)
- [JDK 21](https://adoptium.net/temurin/releases/?package=jdk&arch=any&os=any) 
- [JavaFX SDK 21](https://gluonhq.com/products/javafx/)

### Build and Run Commands
in project root type:
```bash
# Build the project
mvn clean package

# Run the application
chmod +x wordle && ./wordle
```

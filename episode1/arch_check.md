# Checking your Architecture

- Using VS Code / Powershell:
  
  ```sh
  $env:PROCESSOR_ARCHITECTURE
  # Expected output: AMD64
  ```
- Using CMD
  
  ```sh
  # Method 1
  echo %PROCESSOR_ARCHITECTURE%
  # Expected output: AMD64

  # Method 2
  wmic cpu get architecture
  # Expected output: 9
  ```
  

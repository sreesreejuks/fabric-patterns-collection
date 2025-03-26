# Fabric Installation Guide

## Repository Credits

### Fabric Framework
- **Original Creator**: Daniel Miessler
- **Main Repository**: [danielmiessler/fabric](https://github.com/danielmiessler/fabric)
- **Description**: An open-source framework for augmenting humans using AI

### Additional Patterns
- **Repository**: [wmahfoudh/fabric-patterns](https://github.com/wmahfoudh/fabric-patterns)
- **Additional Patterns**: Supplementary collection of AI interaction patterns

## Repository Structure
This repository combines patterns and resources from both:
- Daniel Miessler's original Fabric framework
- wmahfoudh's additional Fabric patterns

## Installation Steps

1. **Download and Install Fabric**
   ```bash
   # Download the latest Fabric binary for Linux (amd64)
   curl -L https://github.com/danielmiessler/fabric/releases/latest/download/fabric-linux-amd64 > fabric

   # Make the binary executable
   chmod +x fabric

   # Move the binary to a system-wide location
   sudo mv fabric /usr/local/bin/
   ```

2. **Verify Installation**
   ```bash
   # Check Fabric version
   fabric --version
   ```

3. **Run Initial Setup**
   ```bash
   # Run the setup to configure directories and keys
   fabric --setup
   ```

## Pattern Sources
- Core patterns from [danielmiessler/fabric](https://github.com/danielmiessler/fabric/tree/main/patterns)
- Additional patterns from [wmahfoudh/fabric-patterns](https://github.com/wmahfoudh/fabric-patterns)

## Optional: Clipboard Support
For clipboard functionality in WSL, install xclip:
```bash
sudo apt update
sudo apt install xclip -y
```

## Contributing
If you're using or extending these patterns, please give proper attribution to:
- Daniel Miessler (Original Fabric Framework)
- wmahfoudh (Additional Patterns Repository)

## Upgrading
To upgrade to the latest version, simply repeat the download and install steps:
```bash
curl -L https://github.com/danielmiessler/fabric/releases/latest/download/fabric-linux-amd64 > fabric
chmod +x fabric
sudo mv fabric /usr/local/bin/
```

## License
Please refer to the original repositories for licensing information:
- Fabric Framework: [MIT License](https://github.com/danielmiessler/fabric/blob/main/LICENSE)
- Fabric Patterns: [GNU General](https://github.com/wmahfoudh/fabric-patterns/blob/main/LICENSE)


## Additional Notes
- Ensure you have an OpenAI API key or another supported AI model configured
- Some features may require additional dependencies

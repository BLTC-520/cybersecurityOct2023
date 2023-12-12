# Cybersecurity Assignment Instructions

## Prerequisites

1. **Create a GitHub Account**
   - Visit [GitHub](https://github.com/) and sign up for an account.

2. **Download and Install Git**
   - Follow online resources to download and install Git.
   - [GitHub Tutorial](https://youtu.be/1ibmWyt8hfw)

## Getting Started

1. **Clone the Repository**
   - Open your command prompt (cmd).
   - Run the following command to clone the repository to your local machine:
     ```
     git clone [repository_url]
     ```

2. **Navigate to the Repository**
   - Change your directory in the command prompt to the location of the cloned repository.

## Running hashcat

1. **Open Command Prompt**
   - Launch the command prompt on your machine.

2. **Execute hashcat Command**
   - Run the hashcat command to break the hash files. Example for `hash1.txt`:
     ```bash
     hashcat --help
     hashcat -m [hash_mode] -a [attack_mode] hash1.txt [options]
     ```

   - Optional Parameters:
     - `--keep-guessing`
     - `--force`

   - Refer to `hashcat --help` for detailed information on available options.

3. **Learn from Example**
   - View the example provided for `hash1.txt` for reference.
     ![hash1 Example](https://github.com/BLTC-520/cybersecurityOct2023/assets/125104831/86490d3d-e989-48ed-bae6-611cf5cfca84)

4. **Repeat for Other Hash Files**
   - Apply the same process for other hash files (hash2.txt to hash5.txt).

## Conclusion

Feel free to explore and learn from the hashcat command. If needed, refer to the hashcat documentation for further details.

Good luck with your cybersecurity assignment!

## Don't run inside the virtual machine as it only has 4GB RAM/8GB RAM at max. Use your fren's computer (RTX4090 / Macbook M3 MAX), as long as got graphic card, it will sped up your progression. DO IT EARLY PLEASE. (Time and device is obstacle for this assignment)





# Babuk Ransomware Decryption Guide

**Warning**: When decrypting, save important encrypted files and delete them only after thorough verification! Babuk ransomware is known to be dangerous, as it can damage files during the decryption process due to a lack of metadata checks.

## Decryption Instructions

Follow these steps carefully to decrypt files affected by the Babuk ransomware. Be sure to back up your encrypted files before proceeding, as the decryption process may corrupt files if not handled properly.

### Steps

1. **Upload Decryptor**  
   Upload the `encryp_dec.out` file to the `/tmp` directory on your system.

2. **Set Executable Permissions**  
   Grant executable permissions to the decryption file by running the following command:
   
   ```shell
   chmod +x ./encryp_dec.out
   ```

3. **Run Decryptor**  
   Execute the decryptor with the directory containing your encrypted files. Replace `/your_dir` with the actual path to the directory where your encrypted files are located.
   
   ```shell
   ./encryp_dec.out /your_dir
   ```

### Important Notes
- **Backup First**: Make sure to backup your encrypted files before running the decryptor. Verify the integrity of the decrypted files before deleting any backups.
- **Metadata Caution**: Babuk ransomware may cause file damage as it does not verify metadata during decryption. Proceed with caution to avoid data loss.

For any questions or further assistance, consult a cybersecurity professional.

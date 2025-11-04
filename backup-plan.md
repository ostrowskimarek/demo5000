## Basic Guide to Home Data Backup

Regular data backups protect you from accidental loss, hardware failure, or ransomware attacks.  
A proper strategy combines **local** and **cloud** backups.

### Backup Types
| Type         | Description                                      | Example tools        |
|---------------|--------------------------------------------------|----------------------|
| Local backup  | Stored on external drive or NAS                 | rsync, Time Machine  |
| Cloud backup  | Stored on remote servers over the Internet      | Google Drive, Backblaze |
| Hybrid        | Combination of local + cloud                    | Duplicati, rclone    |

### Good Practices
- Keep at least **3 copies** of important data.  
- Store backups in **2 different physical locations**.  
- Test restoration regularly — a backup that can’t be restored is useless.  
- Encrypt sensitive data before uploading it to the cloud..
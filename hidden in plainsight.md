# **Hidden in Plainsight**

After downloadin the file, open terminal and type:

      sudo exiftool <file_path/file_name>
<img width="1856" height="905" alt="Screenshot from 2026-01-31 03-39-01" src="https://github.com/user-attachments/assets/56cf8a0f-48c3-4cea-b7d6-780a181c3c1c" />

Comment is suspicious, copy the text and paste it on base64 decode
<img width="1856" height="937" alt="Screenshot from 2026-01-31 03-42-03" src="https://github.com/user-attachments/assets/e9771ab7-f705-4c6e-9c2e-fa8233b07ada" />

Copy the text after the steghide: to decode
<img width="1847" height="932" alt="Screenshot from 2026-01-31 04-16-42" src="https://github.com/user-attachments/assets/0b236ecd-fd2c-4f28-b0af-249826a5e7d3" />

Back to terminal, use:

      steghide extract -sf <file_path/file_name> -p p4zzword

- -sf to specify the stegofile
- -p for pasphrase, which is p4zzword
<img width="877" height="81" alt="Screenshot from 2026-01-31 03-59-47" src="https://github.com/user-attachments/assets/687759f8-446b-4449-9ac4-4dcef2e7e09d" />

Then use cat to see what's inside the txt file.
<img width="643" height="102" alt="Screenshot from 2026-01-31 04-00-01" src="https://github.com/user-attachments/assets/ef9dd552-90e1-4407-b5f7-4afe56eabaa0" />

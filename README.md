(English)
Instructions for the reviewer
To verify the code:
- Log in to the EC2 instance
- Check if the upload_s3.py script is in the home directory (cd /home/ubuntu -> ls)
- Run the code: python3 upload_s3.py
- Informations will be collected to the file named ec2InsDatafile and output will be uploaded into S3 bucket (system_info<instance-id>.txt)



(Polish)
Opis dla osoby sprawdzającej:
Aby sprawdzić działanie programu:
- Zaloguj się na instancję EC2
- Sprawdź czy program upload_s3.py znajduje się w katalogu domowym (cd /home/ubuntu -> ls)
- Uruchom go komendą: python3 upload_s3.py
- Informacje zostaną zebrane do pliku o nazwie ec2InsDatafile i wynik zostanie też wysłany do S3 (system_info<instance-id>.txt)



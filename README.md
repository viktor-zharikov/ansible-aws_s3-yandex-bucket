# ansible-aws_s3-yandex-bucket
if y want use aws_s3 ansible module for put file to yandex s3 bucket, y mast edit ~/.local/lib/python3.7/site-packages/boto3/s3/transfer.py
like on screenshots:

after, put list del get geturl function worked, but module get error about ACL, y can ignore this errors, it work fine:)

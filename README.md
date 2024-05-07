# Turn off EC2
 This action turn off an EC2 instance to AWS.

### example
```yml
uses: archaic10/turn-off-ec2@main
with:
    access-key-id: ${{ secrets.ACESS_KEY_ID }}
    secret-access-key: ${{ secrets.ACESS_SECRET_KEY }}
    region: ${{ secrets.REGION }}
    id-instance: ${{ secrets.ID_INSTANCE }}   
```
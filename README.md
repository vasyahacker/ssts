# ssts
Sites speed test script

### Requirements
curl

### Usage
```bash
echo "https://mysite.com" > ~/sites4test.txt
echo "https://anothersite.com" >> ~/sites4test.txt
./ssts
```
![example](example.png)

### Reference

Transfer time = Total - Starttransfer

Page generation time = Pretransfer - Starttransfer

etc...

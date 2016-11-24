```xml
sudo chmod +x testkey.pk8
sudo chmod +x testkey.x509.pem
sudo chmod +x signapk.jar
```
copy to /bin</br>
".bashrc"
```xml
export PATH=~/bin:$PATH
```
```xml
java -jar signapk.jar testkey.x509.pem testkey.pk8 old new
```


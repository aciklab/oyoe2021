### Basit Web Sunucusu Örneği
- İlk olarak `cd`komutu ile /opt dizini altına gidilir
  ```
  cd /opt
  ```
- `nano`komutu ile index.html adında bir dosya açılır ve içerisinde [index.html](https://github.com/aciklab/oyoe2021/basit-web-sitesi/index.html) dosyasındaki `html` kodları yazılır.
- `ip a` komutu ile makinenin ip adresi öğrenilir.
  ![word-image-703](https://user-images.githubusercontent.com/11041014/131214755-dfe12bf1-ba52-4467-98b3-47ad897e5e69.png)

- `pwd` komutu ile /opt dizini altında oldunduğu kontrol edilir.
- python3 komutu ile 5555 portundan hizmet verecek basit bir web hizmeti açılır. Bu komut bulunduğu dizini web üzerinden yayınlar.
  ```
  python3 -m http.server 5555
  ```
- İnternet tarayıcısına girerek oluşturduğunuz web sitesine ip adresi ve 5555 portu yazılarak ulaşılabilir.
  ```
  http://192.168.100.6:5555
  ````

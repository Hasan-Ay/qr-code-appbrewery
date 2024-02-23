...

#   Qr Code / NodeJS - NPM / App Brewery - Angela Yu Project

...

# A fully responsive EXAMPLE QR Code generator project written in JS (NodeJS - NPM).

* This project is an example that was built along with a Udemy course (Angela Yu - App Brewery) showing how to create a responsive QR code generator in JS (NodeJS - NPM). Every part of this project is sample code.

* In this project, the website or other information entered by the user is output as a PNG as a QR code. Additionally, the data 'input' entered by the user is saved in a text file.

* Bu proje Angela Yu - AppBrewery tarafından hazırlanan bir QR Code üretici  örnek yapımını göstermektedir. Projenin her bir parçası örnek koddur.

* Bu projede kullanıcının girdiği web sitesi ve ya diğer bilgiler QR Code olarak PNG halinde çıktı vermektedir. Ayrıca kullanıcının girdiği veriler bir text dosyasında kaydedilmektedir.

## QR Code Generator Nasıl kurulur ?

* İlk olarak Console da bash üzerinden 'npm init -y' yazarak npm kurulumunu yapıyoruz. Eklenen Package.json dosyasında "main": "index"; yazan kısmın altına "type": "module"; yazıyoruz ve ekleyeceğimiz modüllerin çalışması için dosyaları şimdi import edeceğiz.

* Console'u açtıktan sonra Bash üzerinden 'npm i inquirer' kurmamız gerekmektedir. Inquirer'ı kullanıcıdan girdi aldıktan sonra ona QR Code'u çıktı olarak vermemiz için kullanıyoruz.

* Ardından "npm -i qr-code" ile QR Code generator'umuzu ekliyoruz. Bu kodlar yüklendikten sonra console'a girerek "node index.js" yazarak input girmemiz gerekecektir. Kodlar hazır olduğundan dolayı sadece yüklenecek olan dosyalar burada gerekmektedir. 

* Input girildikten sonra yeni png dosyası oluşmakla beraber text dosyasının içerisine kullancının yazdığı girdi not alınır.


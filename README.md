## Upload no servidor AWS

Fazendo upload de imagens no servidor AWS, da amazon, utilizando **_NodeJS_** e **_ReactJS_**.

### Back-end

As informações da imagem ( nome, tamanho, url, etc ) foram salvas no banco de dados _MongoDB_, e a imagem em si está salva no armazenamento _AWS S3_ da amazon.

Usei a biblioteca _aws-sdk, multer e multer-s3_, para fazer o upload das imagens e conectar o o back-end no servidor AWS.

### Front-end

Utilizei o biblioteca _react-dropzone_ para permitir o arrasto de imagens para upload.

Toda animação de loading foi feita usando a biblioteca _react-circular-progressbar_.

Só é permitido fazer upload de imagens, caso o usuário tente outros tipos de arquivos, o sistema irá informá-lo no mesmo momento.

##### Demonstração

<kbd><img src="https://github.com/viniciusmendite/PrintScreen/blob/master/uploadImage/uploadImage.gif" alt="screen" width="720" height="340" /></kbd>

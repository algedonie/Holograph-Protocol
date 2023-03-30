<h1 align="center">Holograph Protocol Operator Kurulum Rehberi

## Helo, mainnete geçmiş olan Holograph Operator kuranlara bir ayrıcalık olacağından bahsediyor. Operator'ü kurduktan sonra Discord'dan rol alıyoruz. Güncellemeler için bizi takipte kalın. Sağ üstten yıldızlayıp forklamayı unutmayalım. Sorularınız olursa: [LossNode Chat](https://t.me/LossNode)



![image](https://user-images.githubusercontent.com/101462877/228777083-3b57514c-f8ba-4749-9391-b474b5ed5136.png)

## Minimum sistem gereksinimleri:
NODE TİPİ | CPU     | RAM      | SSD     |
| ------------- | ------------- | ------------- | -------- |
| Testnet | 2          | 2         | 50GB  |


## Holograph Protocol için önemli linkler:
- [Website](https://www.holograph.xyz/)
- [Twitter](https://twitter.com/holographxyz)
- [Discord](https://discord.gg/holograph)
  
# Kuruluma başlıyoruz. Root yetkisi alın.

```
sudo su
cd $HOME
```
  
## Sunucuyu güncelleyin.

```
sudo apt update && sudo apt upgrade -y
```

## Node.js/npm yükleyin.

```
sudo apt install nodejs -y
```

Node.js versiyon kontrol
```
node -v
```

```
sudo apt install npm -y
```

npm versiyon kontrol
```
npm -v
```

## Holograph CLI yükleyin.

```
npm install -g @holographxyz/cli
```

## Alchemy üzerinden endpoint alalım.

![image](https://user-images.githubusercontent.com/101462877/198358298-d6be4399-154d-4873-bc8c-e6f37db80860.png)

## [Alchemy](https://dashboard.alchemy.com/) üzerinde hesabınız yoksa hesap açıp `Create App` diyoruz.

![image](https://user-images.githubusercontent.com/101462877/198358599-14a29270-fd3d-4654-9f0d-503faa7992b2.png)

## Bir isim girip `Create App` diyelim. Ethereum için Goerli ya da Polygon için Mumbai seçebilirsiniz. Testnet olmalı.

![image](https://user-images.githubusercontent.com/101462877/198358754-a9f2f648-4895-429a-aa73-e240a3fcfe5e.png)

## Oluşturduğumuz App için `View key`'e tıklayalım.

![image](https://user-images.githubusercontent.com/101462877/198359002-9c032e82-7071-4a06-9868-0d6343f6dada.png)

## Açılan kısımda `https` kısmını bir yere kopyalayalım.

## Sonrasında herhangi bir BOŞ METAMASK cüzdanınızın private key'ini alın, lazım olacak.

![image](https://user-images.githubusercontent.com/101462877/228778722-e081280c-c37e-418b-bc98-c01a5b194339.png)

![image](https://user-images.githubusercontent.com/101462877/228778782-244d20c5-96cc-42e7-bb9c-31e4cee724c7.png)

## Terminale dönerek aşağıdaki komutu yazıyoruz.


```
holograph config
```

<img width="1192" alt="Ekran Resmi 2023-03-30 11 39 45" src="https://user-images.githubusercontent.com/101462877/228779887-b36859be-b08c-4fcb-9dff-1f6eb224dd7b.png">

Sırasıyla `ağ`, `Alchemy'den aldığınız https ile başlayan link`, `BOŞ METAMASK private key`, `sizin belirlediğiniz şifre` giriyoruz.


## Faucet alarak devam ediyoruz.
```
holograph faucet
```

![image](https://user-images.githubusercontent.com/101462877/228780633-dfe2d7b6-16c0-469a-981f-7eb947ce0a1f.png)


## Bond işlemi.
```
holograph operator:bond
```

![image](https://user-images.githubusercontent.com/101462877/228782008-a74511c6-5efd-49e5-acad-2f9fad681122.png)


## Dilerseniz [Discord](https://discord.gg/holograph)'a giderek Operator rolü alabilirsiniz, ileride bazı ayrıcalıklar tanınacağı belirtilmiş.

![image](https://user-images.githubusercontent.com/101462877/228782792-f5770523-446e-426e-adab-e3e6d508ce9e.png)


# Sorularınız ve merak ettikleriniz için:

![image](https://user-images.githubusercontent.com/101462877/228602970-a209f2b2-3269-48e4-9d6a-7d04004bf5f7.png)


- [Telegram](https://t.me/lossnode)
- [Discord](https://discord.gg/bJZA4NyPjz)


# [Fleek Network Turkish Telegram](https://t.me/FleekNetworkTurkish)

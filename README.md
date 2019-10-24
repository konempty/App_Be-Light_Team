# App_Be-Light_Team
# BeLight

```BeLight(�����Ʈ)�� ������ �������ǽ��� ���� �����ϰ�,```
``` ���ϴ� ��ҿ��� ã�� �� �ֵ��� ���� �̵������ִ� ����``` 

[**���� ��������**](https://be-light.store)

## WEB

## Installation

**Download Git** [here](https://git-scm.com/).
**Download Node** [here](https://nodejs.org/en/)

## ����� Ŭ��

git clone ��ɾ��, BeLight ����Ҹ� Ŭ���Ѵ�.

    git clone https://github.com/be-light/be-light.git

## ��Ű�� ��ġ

���� �������Ҷ�, nodemon�� ����ϹǷ�, ���� ��ġ�Ѵ�.

    npm install -g nodemon

��ġ�� �Ϸ�Ǹ�, package.json ���� ��Ű������ ��ġ�Ѵ�.

    npm install

## �����ϱ� ���� �غ�
DB����, JWT ���Ű, Google API Key, Ǫ���� ���� Firebase Server Key ���� �������־�� �Ѵ�.

    /* ������Ʈ �ֻ��� ����� .env ���� */
         HTTP_PORT=80
         HTTPS_PORT=443
         MYSQL_DATABASE=DB�̸�
         MYSQL_USERNAME=�����̸�
         MYSQL_PASSWORD=��й�ȣ
         MYSQL_HOST=������ (������ ���� remotemysql.com ���� DB�� ����߽��ϴ�)
         MYSQL_DIALECT=DB ���� (ex - mysql)
         NODE_ENV=development
         FCM_SERVER_KEY=Firebase ServerKey
  
  ---

```javascript 
/* src/utils/jwt.ts */
this.jwtObj.secret  =  "��ū������ ����� ���Ű �Է�";
```

---

```javascript
/* src/views/*.pug  ���� �߱� ���� Google API_KEY �Է� */
script(async  defer  src="https://maps.googleapis.com/maps/api/js?key=YOUR_API_KEY&libraries=places")
```
## ���� ����

    /* ��Ʈ ���丮���� �͹̳� ��ɾ� ���� */
    npm run dev:start // Webpack���� ���鸵�� ������ ����

---

## Used

![enter image description here](https://i.imgur.com/OgWV5pU.jpg)

## ���� ȭ��

![enter image description here](https://i.imgur.com/Y2SYZAu.png)

![enter image description here](https://i.imgur.com/LXQyuar.png)

![enter image description here](https://i.imgur.com/4DQOLtA.png)

## APP

## ����� Ŭ��

git clone ��ɾ��, BeLight ����Ҹ� Ŭ���Ѵ�.

    git clone https://github.com/be-light/be-light.git
    
## Installation

Demo ������ �Ʒ� ��ũ���� ���� �� �ֽ��ϴ�.

[user.apk](https://be-light.store/upload/user.apk)
[host.apk](https://be-light.store/upload/host.apk)



## ���� ���� �� ���

```javascript
"/app/src/main/java" //�ڹټҽ��ڵ�
"/app/src/main/rs" // ���࿡ �ʿ��� ���ҽ����ϵ�
"/build.gradle", "/gradle/build.gradle" // ���� ��������
```

## User APP ���

### ȸ������ �� �α���
![enter image description here](https://i.imgur.com/iONvRgP.png)
**Register**��� ���ִ� ��ư�� ������.
![enter image description here](https://i.imgur.com/v94zhqi.png)
�� ȭ�鿡�� ���̵�, ��й�ȣ�� ȸ�����Կ� �ʿ��� ������ �Է��� 
�Ʒ��� �ִ� **Sign Up**��ư�� ������ ȸ�������� �Ѵ�.
ȸ�����Կ� �����ϸ� �ٽ� ó��ȭ������ ���ƿ��� �ȴ�.
�� ó��ȭ�鿡�� **Sign In**��ư�� ������ ���̵�� ��й�ȣ�� �Է��� �� �ִ� â�� �����.
�� â�� ȸ�������Ҷ� ����� ���̵�� ��й�ȣ�� �Է��� **Log In**��ư�� ������ �α����Ѵ�.
### ����
![enter image description here](https://i.imgur.com/4VWsn2i.png)
�α����� �ϸ� ������ ���̰� �ȴ�. 
���� �� ĳ����濷�� **+/-��ư**�� ������ �ñ�� ���� ������ ������ �� �ְ�
�� �� �˻�â�� �ڽ��� ���� �ñ�ų� ã�����ϴ� ������ �˻��Ѵ�.
![enter image description here](https://i.imgur.com/GQsuJCZ.png)
�˻�����߿��� ��Ŀ�� ������ Host�� ���� ������ ������ ���.
������ Host�� ���並 ���� ������ �����ư�� ������ ���䰡 ���δ�.
������ Host ������ ��� **����**��ư�� ������.
![enter image description here](https://i.imgur.com/VFkJwkG.png)
�����ư�� ������ ������ ȣ��Ʈ�� ���� �ñ������ ���� ã�� ��ҷ� ������� ������ �� �ִ�.
���� �ñ�� ��ҿ� ã����Ұ� ��� ���õǸ� Ȯ�ι�ư�� �����ư���� ���Ѵ�. 
![enter image description here](https://i.imgur.com/zUBUO9m.png)
�����ư�� ������ ������ ������ Ȯ���ϰ� ������ Ȯ���� �� �ִ�.
���������� Ȯ�������� �Ʒ��� �ִ� �����ư�� ������ ������ ��û�� �� �ִ�.

### ���ñ�� ã��
������ ȣ��Ʈ�� Ȯ���ؼ� ������ ���ָ� ����ڿ��Դ� **Ǫ�ø޽���**�� ���Եǰ�
���� �ñ��� ������ �ð��� ���缭 ���� �ñ� Host�� ���� 
���Կ��� ���� **QR�ڵ�**�� �޸� ���� �޾��ְ� ���� �޾��ش�.

���� ã�ư���� ������ �ð��� ���缭 ���� �ñ� Host�� ����
���� Ű�� �ֹ��������� �´� �ֹ��� ã�Ƽ� �� ã�� ��ư�� ������ ī�޶�� **QR�ڵ�**�� ������ ���� ã�ƿ� �� �ִ�.
## HOST APP
### ȸ������ �� �α���
User�� ������ �����ϴ�.
### ȣ��Ʈ�߰�
![enter image description here](https://i.imgur.com/4he3K1a.png)
![enter image description here](https://i.imgur.com/H79i6FB.png)
�α������� ùȭ�鿡�� �Ʒ��ʿ� **+��ư**�� ������ ���̾� �αװ� �߰� ���⿡ Host������ �ְ� �߰� ��ư�� ������ Host�� �߰��ȴ�.
### ���þ��ֱ�
![enter image description here](https://i.imgur.com/GKdn4fa.png)
�ڽ��� �����ϴ� Host�� ������ ��ϵǾ��ٴ� **Ǫ��**�� ���� ���� �Ѱ� ������ �ֹ������� ������.
���⼭ �ֹ��� ������ ���� ������ �ϰų� ���� �� ���ִ�.
	������ �ϸ� ������ �ð��� ���� �մ��� ���� �ǰ� �մ��� ���� **QR�ڵ�**�� �޸� ���� �޾��ְ�
![enter image description here](https://i.imgur.com/3krAorT.png)
�ֹ��������� ���ñ���ư�� ������ ī�޶�� **QR�ڵ�**�� ��� ���� �þƵд�.
### �������ֱ�
�մ��� ������ �ð��� �°� ���� ���� �����ְ� �մ��� ������ ���� �޸� **QR�ڵ�**�� ���
	������ �Ǹ� �׶� ���� �����ָ� �ȴ�.
## ��Ÿ

### ������Ʈ ���� (Change Log)
2019-10-24 **1.0.0ver.**


###  License
MIT License

### Contact

Design, PM, Publisher:  **������**(donghun4754@gmail.com)
 Backend API:  **�ڰ���**(yeonkevin@naver.com)
Android Native App: **���Ѻ�**(1117plus@gmail.com)
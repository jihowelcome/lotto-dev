# lotto-dev

## frontend : react
### 구성
* 헤더 : 최근 당첨 번호
* 네비 : 로또 종류, 번호 추출, 과거 당첨
* 바디 : 번호 추출, 과거 당첨
탭으로 로또7, 로또6, 미니로또 변환
네비게이션 클릭 시 해당 영역으로 점프(한 페이지에 전부 작성), 로또 종류는 화면 전체 로또 종류 변경

### 환경 설정
#### 소스코드 빌드

```
apt-get update
apt-get install build-essential libssl-dev
wget -q -O - https://packages.cloudfoundry.org/debian/cli.cloudfoundry.org.key | sudo apt-key add -
```

#### NVM

```
https://github.com/nvm-sh/nvm#installing-and-updating # 사이트에서 인스톨 커맨드 복사 ubuntu는 wget
wget -qO- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.3/install.sh | bash
```

##### 설정파일 리로드

```
source ~/.bashrc
```

#### NODE.JS

```
nvm install node
```

에러 `GLIBC_2.28' not found (required by node) 발생 시 node버전 변경

```
ldd --version # GLIBC 버전 확인
sudo apt-get remove nodejs
nvm install 14.21.2
```

#### 리액트

```
npm init react-app web  # 리액트 앱 생성
cd web
npm start # 리액트 실행
```

구름 IDE의 경우 실행URL과 포트에서 포트3000으로 설정

## backend : python
### 

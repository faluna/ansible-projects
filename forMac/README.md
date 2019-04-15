# ansible project for mac

mac のローカル環境を ansible を使って構築する．主に homebrew, cask, mas, fonts の導入まで  
This is the constructor that use ansible for mac. Mainly up to the introduction brew app, cask app, mas app and fonts for mac.

---

## 必要要件(Requirement)

---

mac

---

## インストール(install)

---

###### Command Line Developer Tools のインストール(instruction of Command Line Developer Tools)

```bash:terminal
xcode-select --install
```

###### homebrew のインストール

```bash:terminal
/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
```

- homebrew の確認

```bash:terminal
brw doctor
```

###### ansible インストール

```bash:terminal
brew install ansible
```

###### git のインストール

```bash:terminal
brew install git
```

###### github から ansible-project リポジトリのクローン

```bash:terminal
git clone https://github.com/faluna/ansible-projects.git ~/ansible-project
```

###### ansible 実行

```bash:terminal
cd ~/ansible-prjects/forMac
ansible-playbook -i default site.yml
```

## 参考サイト

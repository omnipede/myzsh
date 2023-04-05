# myzsh

zsh 설정 스크립트

# 실행 방법

* 스크립트 실행

```sh
sh -c "$(curl -fsSL https://github.com/omnipede/myzsh/blob/master/ubuntu.sh)"
```

* `~/.zshrc` 에 `plugins` 필드에 다음 코드 삽입

```sh
plugins=(git zsh-autosuggestions zsh-syntax-highlighting)
```

* `~/.zshrc` 반영

```sh
$ source ~/.zshrc
```
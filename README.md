# yew-docker

## Setup
めっちゃ時間かかる(もう少し環境構築を早くしたい)
docker周りのエラーは保証できません
```
1. git clone git@github.com:You-saku/yew-docker.git
2. cd rust-docker
3. make init
4. make sh
----- コンテナ内　-----
5. cd yew
6. trunk serve --address 0.0.0.0 --port=3000
7. 最後に「0.0.0.0:3000」を開く
```

## Reference
https://yew.rs/ja


## お役立ち情報
* [localhost:8080は動かない](https://stackoverflow.com/questions/72309114/docker-container-didnt-send-any-data?noredirect=1#comment127746034_72309114)
trunk serve --address 0.0.0.0 --port=3000

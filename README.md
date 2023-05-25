# next_study_meeting

## 使い方

```bash
git clone https://github.com/85yago/next_study_meeting.git
```
で`next_study_meeting`フォルダを落としてくるのでそれをvscodeで開く。

次に、F1からのrebuildをする。
ひょっとすると既存のimageやcontainerを消さなきゃいけないかも？

コンテナで開いたら`yarn`して`npx prisma db push`する。

最後に`yarn build` & `yarn start`する。

macだと`yarn dev`は微妙に使えないかも。winなら使おう。buildしなくて良い。

# yorimichi-media

「AIと寄り道編集部」の、Instagram・Threadsへ投稿する画像の公開置き場。

- InstagramとThreadsのAPIは、画像をインターネットから見えるURLでしか受け取らないため、投稿する画像だけをここに置く
- 書き込むのは常時接続PCの自動投稿（`ai_yorimichi_master` の `automation/publisher/src/lib/media.mjs`）だけ。`images/<キューのid>/` に入れ、コミット固定のURLを使う
- 入るのは公開済みのSNS画像だけ。原稿や未公開の画像は置かない

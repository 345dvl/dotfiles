## まずインストールが必要で忘れそうなもの
- Homebrew

## karabiner-elements
ln -s ~/dev/dotfiles/.karabiner-elements/fn.json ~/.config/karabiner/assets/complex_modifications/fn.json
※相対パスだとアクセスできないことがあるため絶対パスでシンボリックリンクを貼る
karabiner-elementsでComplex Modifications→Add rule→インポートしたルールをEnable All

## その他アプリ設定
### Mos
- スムーズスクロールをOFFにするとstep数が効かなくなるためONに
- SpeedをMax、DurationをMinにしStepはお好みで
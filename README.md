# Wezterm Settings
## Install
```bash
brew install koekeishiya/formulae/skhd
```
## File directory
```bash
cd $HOME/.config/
git clone git@github.com:seesaw-monster/skhd.git
```
## Start service
```bash
skhd --start-service
```
****ターミナルを再起動しないと設定が反映されない時がある

## キーバインド設定
### ウィンドウフォーカス移動
- `Alt + h/j/k/l`: 隣接するウィンドウまたはディスプレイにフォーカス移動

### ウィンドウ移動
- `Shift + Cmd + h/l`: 同一ディスプレイ内でウィンドウを左右に移動
- `Shift + Cmd + j/k`: ウィンドウを上下のモニタに移動（フォーカス自動追従）

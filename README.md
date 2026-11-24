# nitro-3D

## 翠緑の谷

WebGPU と three.js (r180, `WebGPURenderer` + TSL) で作った、iPhone で見られるファンタジーの3D空間です。森、川、滝、湖、大樹のある谷を見回せます。
`index.html` 1ファイルで完結しており、ビルドは不要です。

- WebGPU 対応ブラウザ (iOS 26 以降の Safari など) では WebGPU で描画し、非対応の場合は自動で WebGL 2 に切り替わります。右上のバッジで確認できます。
- 操作: ドラッグで見回す / ピンチ (またはホイール) で拡大縮小 / 下のボタンで視点切り替えと自動回転。

### ローカルで見る

```sh
npx serve .
```

同じ Wi-Fi の iPhone から表示された URL を開きます (WebGPU は HTTPS か localhost が必要なため、LAN 経由の HTTP では WebGL 2 で動きます)。

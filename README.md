# walletdeeplink

1. tokenpocket
https://help.tokenpocket.pro/developer-cn/mobile-wallet/deeplink

拉起钱包用Dapp浏览器打开链接
```
<a href='tpdapp://open?param={}'>Open TokenPocket to open url</a><br/>
```
```
{
	"url": "https://dapp.mytokenpocket.vip/referendum/index.html#/",
	"chain": "EOS", //dapp支持的网络
	"source": "xxx" //来源，开发者自定义
}
```

2.metamask

https://metamask.github.io/metamask-deeplinks/#

```
https://metamask.app.link/dapp/www.google.com
```

3.imtoken
https://imtoken.gitbook.io/developers/products/deep-linking

```
imtokenv2://navigate/DappView?url=https://fee.token.im/eth
```

4.Trust Wallet
https://developer.trustwallet.com/deeplinking

Due to Apple restrictions, browser was removed from the iOS app

https://github.com/satoshilabs/slips/blob/master/slip-0044.md

195	0x800000c3	TRX	Tron

```
https://link.trustwallet.com/open_url?coin_id=60&url=https://compound.finance
```

5.MathWallet
https://blog.mathwallet.org/?p=3389

```
mathwallet://mathwallet.org?action=link&value=http://dapp.mathwallet.xyz/polkadot/#/kusama
```




only support walletconnect 
1.Rainbow
2.Argent


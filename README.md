# renovate.config

```json
{
    "extends": ["github>m2en/renovate.config"],
    "enableManagers": ["..."]
}
```

デフォルトではどの依存関係も Renovate は触れないよう制限しています。

`enableManagers` を設定して Renovate が監視対象にするエコシステムを指定してください。

- [Managers - Renovate Docs](https://docs.renovatebot.com/modules/manager/)

レビューの自動承認は renovate-approve を利用することで解決できます。

- [renovate-approve - GitHub App](https://github.com/apps/renovate-approve)

----

この Renovate Preset は [m2en](https://github.com/m2en) が自分で使うために設定しているため、自分でカスタマイズしたい場合は Fork することをおすすめします。

- [Configuration Options - Renovate Docs](https://docs.renovatebot.com/configuration-options/)

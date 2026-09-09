# 88API-Image-Gen (self-hosted)

自托管的 Codex 插件市场，提供 `88api-image-gen` 插件（基于 88api.ai 的
GPT-Image-2.5 Flare / Sunburst 模型）。

本仓库为 `blackdm666/88API-image-gen` 的自托管副本，主要用于个人稳定使用，
已将默认模型切换到 `gpt-image-2.5-flare`、高精度档 `gpt-image-2.5-sunburst`。
上游仓库未声明开源许可证，如需对外公开分发请自行确认授权情况。

```powershell
codex plugin marketplace add <本仓库 URL>
codex plugin add 88api-image-gen@88api-plugins
```

然后新建线程使用 `@88API-Image-Gen`。

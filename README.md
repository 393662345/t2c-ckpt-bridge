# t2c-ckpt-bridge

临时中转仓库：通过 GitHub Actions 的海外网络下载 TargetDiff 预训练权重
（Zenodo record 14041881，CC-BY-4.0），并以 Release 附件形式提供下载，
供 t2c 药品研发平台 P2 阶段（3D 口袋条件生成）使用。

- 触发方式：Actions → `fetch-targetdiff-ckpt` → Run workflow
- 产物：Release `targetdiff-ckpt-14041881` 附件 `targetdiff_pretrained_models.tar.gz`
- 校验：size 56,814,038 bytes，MD5 `012e0beafa4c4218761dc4ddcbcc5014`

该仓库只做文件中转，不含业务代码。

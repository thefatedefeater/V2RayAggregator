# TopFreeProxies
[![GitHub Workflow Status](https://img.shields.io/github/workflow/status/alanbobs999/topfreeproxies/sub_merge?label=sub_merge)](https://github.com/alanbobs999/TopFreeProxies/actions/workflows/sub_merge.yml) 

![Watchers](https://img.shields.io/github/watchers/alanbobs999/topfreeproxies) ![Stars](https://img.shields.io/github/stars/alanbobs999/topfreeproxies) ![Forks](https://img.shields.io/github/forks/alanbobs999/topfreeproxies) ![Vistors](https://visitor-badge.laobi.icu/badge?page_id=alanbobs999.topfreeproxies) ![LICENSE](https://img.shields.io/badge/license-CC%20BY--SA%204.0-green.svg)

[仓库介绍](https://github.com/alanbobs999/TopFreeProxies#仓库介绍) | [使用方法](https://github.com/alanbobs999/TopFreeProxies#使用方法) | [节点信息](https://github.com/alanbobs999/TopFreeProxies#节点信息) | [软件推荐](https://github.com/alanbobs999/TopFreeProxies#客户端选择) | [机场推荐](https://github.com/alanbobs999/TopFreeProxies#机场推荐) | [仓库声明](https://github.com/alanbobs999/TopFreeProxies#仓库声明)

## 仓库介绍
本仓库自动化功能全部基于 `GitHub Actions` 实现，如果有需要可以自行 Fork 实现个性化需求。

对网络上各免费节点池及博主分享的节点进行测速筛选出较为稳定高速的节点，再导入到仓库中进行分享记录。所筛选的节点链接在仓库 `./sub/sub_list.json` 文件中，其中大部分为其他 `GitHub` 仓库链接，如果大家有好的订阅链接欢迎提交 PR ，这些链接包含的所有节点会合并在仓库 `./sub/sub_merge.txt` 中。

测速筛选后的节点订阅文件在仓库根目录 `Eterniy`(Base64) 和 `Eternity.yml`(Clash)。同时在仓库的 `./update` 中保留了原始节点链接的的记录。

测速功能使用 [LiteSpeedTest](https://github.com/xxf098/LiteSpeedTest) 在 `GitHub Actions` 环境下实现，所以美国节点较多，不能很好代表国内网络环境下节点可用性，目前正在解决这一问题。

虽然是测速筛选过后的节点，但仍然会出现部分节点不可用的情况，遇到这种情况建议选择`Clash`, `Shadowrocket`之类能自动切换低延迟节点的客户端。

## 使用方法
将以下订阅链接导入相应客户端即可。链接中大部分为 SS 协议节点，少量 Vmess, Trojan ,SSR 协议节点，建议选择协议支持完整的客户端。

- [多协议Base64编码](https://raw.githubusercontent.com/alanbobs999/TopFreeProxies/master/Eternity)
- [Clash](https://raw.githubusercontent.com/alanbobs999/TopFreeProxies/master/Eternity.yml)

另有国内加速链接：

- [多协议Base64编码](https://raw.fastgit.org/alanbobs999/TopFreeProxies/master/Eternity)
- [Clash](https://raw.fastgit.org/alanbobs999/TopFreeProxies/master/Eternity.yml)

>`Clash`链接所使用的配置在仓库`./update/provider/`中，有相应配置文件和以国家分类的`proxy-provider`。
>
>需要其它配置可使用订阅转换工具自行转换。
>自用在线订阅转换网址：[sub-web-modify](https://sub.v1.mk/)

## 节点信息
### 高速节点
高速节点数量: `98`
<details>
  <summary>展开复制节点</summary>

    vmess://eyJ2IjoiMiIsInBzIjoiZ2l0aHViLmNvbS9mcmVlZnEgLSDnvo7lm73liqDliKnnpo/lsLzkuprlt57mtJvmnYnnn7ZDaG9vcGHmlbDmja7kuK3lv4MgNDgiLCJhZGQiOiI0NS43Ni43MS4yMzMiLCJwb3J0IjoiNDY5ODMiLCJ0eXBlIjoibm9uZSIsImlkIjoiNjkwOTkyNTgtMTQ3Ni00NmRkLWE1MWItODRlOTE1ZTk0MWJlIiwiYWlkIjoiMCIsIm5ldCI6IndzIiwicGF0aCI6Ii8xdEdLODJsVS8iLCJob3N0IjoiNDUuNzYuNzEuMjMzIiwidGxzIjoiIn0=
    vmess://eyJ2IjoiMiIsInBzIjoiZ2l0aHViLmNvbS92MnJheWZyZWUgLSDnvo7lm73liqDliKnnpo/lsLzkuprlt57mtJvmnYnnn7ZDaG9vcGHmlbDmja7kuK3lv4MgNDgiLCJhZGQiOiI0NS43Ni43MS4yMzMiLCJwb3J0IjoiNDY5ODMiLCJ0eXBlIjoibm9uZSIsImlkIjoiNjkwOTkyNTgtMTQ3Ni00NmRkLWE1MWItODRlOTE1ZTk0MWJlIiwiYWlkIjoiMCIsIm5ldCI6IndzIiwicGF0aCI6Ii8xdEdLODJsVS8iLCJob3N0IjoiNDUuNzYuNzEuMjMzIiwidGxzIjoiIn0=
    vmess://eyJ2IjoiMiIsInBzIjoi5pel5pysIDAxNyIsImFkZCI6IjQ1Ljc2LjcxLjIzMyIsInBvcnQiOiI0Njk4MyIsInR5cGUiOiJub25lIiwiaWQiOiI2OTA5OTI1OC0xNDc2LTQ2ZGQtYTUxYi04NGU5MTVlOTQxYmUiLCJhaWQiOiIwIiwibmV0Ijoid3MiLCJwYXRoIjoiLzF0R0s4MmxVLyIsImhvc3QiOiIiLCJ0bHMiOiIifQ==
    vmess://eyJ2IjoiMiIsInBzIjoiVVMtT3Blbml0Lm1sIiwiYWRkIjoic2FuZnJhbmNpc2NvbGFmYXlldHRlLmNsdWIiLCJwb3J0IjoiNDQzIiwidHlwZSI6Im5vbmUiLCJpZCI6ImNjMGI0NDY5LWMwZTUtNGVmYi04ZjY5LWE2ZGY2NGRiMjRlZSIsImFpZCI6IjAiLCJuZXQiOiJ3cyIsInBhdGgiOiIvbmV1cm9tYW5jZXIiLCJob3N0Ijoic2FuZnJhbmNpc2NvbGFmYXlldHRlLmNsdWIiLCJ0bHMiOiJ0bHMifQ==
    vmess://eyJ2IjoiMiIsInBzIjoiWzA1LTA0XXxvc2xvb2t8576O5Zu9KFVTKVVTQS9Mb3NBbmdlbGVzXzExIiwiYWRkIjoiNDUuNzYuNzEuMjMzIiwicG9ydCI6IjQ2OTgzIiwidHlwZSI6Im5vbmUiLCJpZCI6IjY5MDk5MjU4LTE0NzYtNDZkZC1hNTFiLTg0ZTkxNWU5NDFiZSIsImFpZCI6IjAiLCJuZXQiOiJ3cyIsInBhdGgiOiIvMXRHSzgybFUvIiwiaG9zdCI6IiIsInRscyI6IiJ9
    vmess://eyJ2IjoiMiIsInBzIjoibWF0dGtheWRpYXJ5LmNvbXznvo7lm70oVVMpVVNBL0xvc0FuZ2VsZXNfMTEiLCJhZGQiOiI0NS43Ni43MS4yMzMiLCJwb3J0IjoiNDY5ODMiLCJ0eXBlIjoibm9uZSIsImlkIjoiNjkwOTkyNTgtMTQ3Ni00NmRkLWE1MWItODRlOTE1ZTk0MWJlIiwiYWlkIjoiMCIsIm5ldCI6IndzIiwicGF0aCI6Ii8xdEdLODJsVS8iLCJob3N0IjoiIiwidGxzIjoiIn0=
    vmess://eyJ2IjoiMiIsInBzIjoi5qyi6L+O6K6i6ZiF6ZKx56eR5oqAMDQzMF/wn4e68J+HuF9VU1/nvo7lm71fNDAiLCJhZGQiOiJzYW5mcmFuY2lzY29sYWZheWV0dGUuY2x1YiIsInBvcnQiOiI0NDMiLCJ0eXBlIjoibm9uZSIsImlkIjoiY2MwYjQ0NjktYzBlNS00ZWZiLThmNjktYTZkZjY0ZGIyNGVlIiwiYWlkIjoiMCIsIm5ldCI6IndzIiwicGF0aCI6Ii9uZXVyb21hbmNlciIsImhvc3QiOiJzYW5mcmFuY2lzY29sYWZheWV0dGUuY2x1YiIsInRscyI6InRscyJ9
    vmess://eyJ2IjoiMiIsInBzIjoiUmVsYXlfXzE1OV83N01iXzYxIiwiYWRkIjoic2FuZnJhbmNpc2NvbGFmYXlldHRlLmNsdWIiLCJwb3J0IjoiNDQzIiwidHlwZSI6Im5vbmUiLCJpZCI6ImNjMGI0NDY5LWMwZTUtNGVmYi04ZjY5LWE2ZGY2NGRiMjRlZSIsImFpZCI6IjAiLCJuZXQiOiJ3cyIsInBhdGgiOiIvbmV1cm9tYW5jZXIiLCJob3N0Ijoic2FuZnJhbmNpc2NvbGFmYXlldHRlLmNsdWIiLCJ0bHMiOiJ0bHMifQ==
    vmess://eyJ2IjoiMiIsInBzIjoiLVYxMCIsImFkZCI6InNhbmZyYW5jaXNjb2xhZmF5ZXR0ZS5jbHViIiwicG9ydCI6IjQ0MyIsInR5cGUiOiJub25lIiwiaWQiOiJjYzBiNDQ2OS1jMGU1LTRlZmItOGY2OS1hNmRmNjRkYjI0ZWUiLCJhaWQiOiIwIiwibmV0Ijoid3MiLCJwYXRoIjoiL25ldXJvbWFuY2VyIiwiaG9zdCI6InNhbmZyYW5jaXNjb2xhZmF5ZXR0ZS5jbHViIiwidGxzIjoidGxzIn0=
    vmess://eyJ2IjoiMiIsInBzIjoiQFNTUlNVQi1WMTAt5LuY6LS55o6o6I2QOnN1by55dC9zc3JzdWIiLCJhZGQiOiJzYW5mcmFuY2lzY29sYWZheWV0dGUuY2x1YiIsInBvcnQiOiI0NDMiLCJ0eXBlIjoibm9uZSIsImlkIjoiY2MwYjQ0NjktYzBlNS00ZWZiLThmNjktYTZkZjY0ZGIyNGVlIiwiYWlkIjoiMCIsIm5ldCI6IndzIiwicGF0aCI6Ii9uZXVyb21hbmNlciIsImhvc3QiOiJzYW5mcmFuY2lzY29sYWZheWV0dGUuY2x1YiIsInRscyI6InRscyJ9
    trojan://e5d46365e25e31d94279c2bcf93390a2@o7cx6bd6t4yjiqsm.xiongsonglin.com:443?allowInsecure=0#github.com%2Fv2rayfree%20-%20%E7%BE%8E%E5%9B%BD%E4%BA%9A%E5%88%A9%E6%A1%91%E9%82%A3%E5%B7%9E%E6%96%AF%E7%A7%91%E8%8C%A8%E4%BB%A3%E5%B0%94%E5%B8%82Go%20Daddy%E9%9B%86%E5%9B%A2%E5%85%AC%E5%8F%B8%2025
    vmess://eyJ2IjoiMiIsInBzIjoiVVMtT3Blbml0Lm1sIiwiYWRkIjoic2FuZnJhbmNpc2NvbGFmYXlldHRlLmNsdWIiLCJwb3J0IjoiNDQzIiwidHlwZSI6Im5vbmUiLCJpZCI6ImNjMGI0NDY5LWMwZTUtNGVmYi04ZjY5LWE2ZGY2NGRiMjRlZSIsImFpZCI6IjAiLCJuZXQiOiJ3cyIsInBhdGgiOiIvbmV1cm9tYW5jZXIiLCJob3N0Ijoic2FuZnJhbmNpc2NvbGFmYXlldHRlLmNsdWIiLCJ0bHMiOiJ0bHMifQ==
    vmess://eyJ2IjoiMiIsInBzIjoi6L+Z5Lqb6IqC54K55Y+q6IO95aSH55So5oiW6ICF6Ziy5q2i5aSx6IGU77yM6Jm954S26LSo6YeP5bm25LiN5piv5b6I5aW977yM5Lmf6K+35L2O6LCD5L2/55SoOikiLCJhZGQiOiI2NS40OS4yMTQuMTg1IiwicG9ydCI6IjMwNjU4IiwidHlwZSI6Im5vbmUiLCJpZCI6IjM1MWM2NGMxLTJmN2QtNDkwMC1hMmQyLThmMDlhNjUwMTYwMyIsImFpZCI6IjAiLCJuZXQiOiJ0Y3AiLCJwYXRoIjoiLyIsImhvc3QiOiI2NS40OS4yMTQuMTg1IiwidGxzIjoiIn0=
    vmess://eyJ2IjoiMiIsInBzIjoiWzA1LTA0XXxvc2xvb2t8576O5Zu9KFVTKVVTQS9Mb3NBbmdlbGVzXzE1IiwiYWRkIjoiNDUuNzYuNzEuMjMzIiwicG9ydCI6IjQ2OTgzIiwidHlwZSI6Im5vbmUiLCJpZCI6IjY5MDk5MjU4LTE0NzYtNDZkZC1hNTFiLTg0ZTkxNWU5NDFiZSIsImFpZCI6IjAiLCJuZXQiOiJ3cyIsInBhdGgiOiIvMXRHSzgybFUvIiwiaG9zdCI6IiIsInRscyI6IiJ9
    vmess://eyJ2IjoiMiIsInBzIjoiVVMtT3Blbml0Lm1sIiwiYWRkIjoiNjUuNDkuMjE0LjE4NSIsInBvcnQiOiIzMDY1OCIsInR5cGUiOiJub25lIiwiaWQiOiIzNTFjNjRjMS0yZjdkLTQ5MDAtYTJkMi04ZjA5YTY1MDE2MDMiLCJhaWQiOiIwIiwibmV0IjoidGNwIiwicGF0aCI6Ii93cyIsImhvc3QiOiIxNTQuOTQuMjE0LjIiLCJ0bHMiOiIifQ==
    vmess://eyJ2IjoiMiIsInBzIjoi6L+Z5Lqb6IqC54K55Y+q6IO95aSH55So5oiW6ICF6Ziy5q2i5aSx6IGU77yM6Jm954S26LSo6YeP5bm25LiN5piv5b6I5aW977yM5Lmf6K+35L2O6LCD5L2/55SoOikiLCJhZGQiOiI0NS43Ni43MS4yMzMiLCJwb3J0IjoiNDY5ODMiLCJ0eXBlIjoibm9uZSIsImlkIjoiNjkwOTkyNTgtMTQ3Ni00NmRkLWE1MWItODRlOTE1ZTk0MWJlIiwiYWlkIjoiMCIsIm5ldCI6IndzIiwicGF0aCI6Ii8xdEdLODJsVS8iLCJob3N0IjoiNDUuNzYuNzEuMjMzIiwidGxzIjoiIn0=
    vmess://eyJ2IjoiMiIsInBzIjoi576O5Zu9IDA2NSIsImFkZCI6InNhbmZyYW5jaXNjb2xhZmF5ZXR0ZS5jbHViIiwicG9ydCI6IjQ0MyIsInR5cGUiOiJub25lIiwiaWQiOiJjYzBiNDQ2OS1jMGU1LTRlZmItOGY2OS1hNmRmNjRkYjI0ZWUiLCJhaWQiOiIwIiwibmV0Ijoid3MiLCJwYXRoIjoiL25ldXJvbWFuY2VyIiwiaG9zdCI6InNhbmZyYW5jaXNjb2xhZmF5ZXR0ZS5jbHViIiwidGxzIjoidGxzIn0=
    vmess://eyJ2IjoiMiIsInBzIjoi576O5Zu9IiwiYWRkIjoiMTA0LjI0My4yNi4xMTIiLCJwb3J0IjoiMjE3MzUiLCJ0eXBlIjoibm9uZSIsImlkIjoiMDQ1ZjU5NTctMTU3ZC00NjY0LThiOGQtMWIyZmRhMjAyMzg4IiwiYWlkIjoiMCIsIm5ldCI6IndzIiwicGF0aCI6Ii8iLCJob3N0IjoiIiwidGxzIjoiIn0=
    vmess://eyJ2IjoiMiIsInBzIjoiU0dfMTE4MyB8NjYuMjhNYiIsImFkZCI6InNhbmZyYW5jaXNjb2xhZmF5ZXR0ZS5jbHViIiwicG9ydCI6IjQ0MyIsInR5cGUiOiJub25lIiwiaWQiOiJjYzBiNDQ2OS1jMGU1LTRlZmItOGY2OS1hNmRmNjRkYjI0ZWUiLCJhaWQiOiIwIiwibmV0Ijoid3MiLCJwYXRoIjoiL25ldXJvbWFuY2VyIiwiaG9zdCI6InNhbmZyYW5jaXNjb2xhZmF5ZXR0ZS5jbHViIiwidGxzIjoidGxzIn0=
    vmess://eyJ2IjoiMiIsInBzIjoi576O5Zu9IDA3OSIsImFkZCI6IjEwNC4yNDMuMjYuMTEyIiwicG9ydCI6IjIxNzM1IiwidHlwZSI6Im5vbmUiLCJpZCI6IjA0NWY1OTU3LTE1N2QtNDY2NC04YjhkLTFiMmZkYTIwMjM4OCIsImFpZCI6IjAiLCJuZXQiOiJ3cyIsInBhdGgiOiIvIiwiaG9zdCI6IiIsInRscyI6IiJ9
    vmess://eyJ2IjoiMiIsInBzIjoibWF0dGtheWRpYXJ5LmNvbXznvo7lm70oVVMpVVNBL0xvc0FuZ2VsZXNfMTUiLCJhZGQiOiI0NS43Ni43MS4yMzMiLCJwb3J0IjoiNDY5ODMiLCJ0eXBlIjoibm9uZSIsImlkIjoiNjkwOTkyNTgtMTQ3Ni00NmRkLWE1MWItODRlOTE1ZTk0MWJlIiwiYWlkIjoiMCIsIm5ldCI6IndzIiwicGF0aCI6Ii8xdEdLODJsVS8iLCJob3N0IjoiIiwidGxzIjoiIn0=
    vmess://eyJ2IjoiMiIsInBzIjoiUmVsYXlf8J+HuvCfh7hVUy3wn4e68J+HuFVTXzQ2XzE1XzExTWJfOSIsImFkZCI6InVzYS1kYWxsYXMubHZ1ZnQuY29tIiwicG9ydCI6IjQ0MyIsInR5cGUiOiJub25lIiwiaWQiOiJhYmE1MGRkNC01NDg0LTNiMDUtYjE0YS00NjYxY2FmODYyZDUiLCJhaWQiOiI0IiwibmV0Ijoid3MiLCJwYXRoIjoiL3dzIiwiaG9zdCI6InVzYS1kYWxsYXMubHZ1ZnQuY29tIiwidGxzIjoidGxzIn0=
    vmess://eyJ2IjoiMiIsInBzIjoi5qyi6L+O6K6i6ZiF6ZKx56eR5oqAMDQzMF/wn4e68J+HuF9VU1/nvo7lm71fNDAiLCJhZGQiOiJzYW5mcmFuY2lzY29sYWZheWV0dGUuY2x1YiIsInBvcnQiOiI0NDMiLCJ0eXBlIjoibm9uZSIsImlkIjoiY2MwYjQ0NjktYzBlNS00ZWZiLThmNjktYTZkZjY0ZGIyNGVlIiwiYWlkIjoiMCIsIm5ldCI6IndzIiwicGF0aCI6Ii9uZXVyb21hbmNlciIsImhvc3QiOiJzYW5mcmFuY2lzY29sYWZheWV0dGUuY2x1YiIsInRscyI6InRscyJ9
    vmess://eyJ2IjoiMiIsInBzIjoiUmVsYXlfXzE1M181MU1iXzE0NiIsImFkZCI6ImFhLmtheWFsby5jb20iLCJwb3J0IjoiMjYyNjciLCJ0eXBlIjoibm9uZSIsImlkIjoiOTc1N2NkYmEtYzc1Yi00Yjk0LTllMzEtNzk1NmRjN2Q4NTJhIiwiYWlkIjoiMCIsIm5ldCI6IndzIiwicGF0aCI6Ii93aXMiLCJob3N0IjoiYWEua2F5YWxvLmNvbSIsInRscyI6IiJ9
    trojan://f39bd244-f5fe-415c-8b98-a1e5250bf178@fhcarm2.gaox.ml:443?allowInsecure=0#github.com%2Fv2rayfree%20-%20%E7%BE%8E%E5%9B%BD%20%2049
    vmess://eyJ2IjoiMiIsInBzIjoiZ2l0aHViLmNvbS9mcmVlZnEgLSDnvo7lm71DbG91ZEZsYXJl6IqC54K5IDM4IiwiYWRkIjoidXMwMi5nb2dvZ29vLmN5b3UiLCJwb3J0IjoiNDQzIiwidHlwZSI6Im5vbmUiLCJpZCI6ImRiNWQxYWEzLTkwOGItNDRkMS1iZTBhLTRlNmE4ZDRlNGNkYSIsImFpZCI6IjAiLCJuZXQiOiJ3cyIsInBhdGgiOiIvZ28iLCJob3N0IjoidXMwMi5nb2dvZ29vLmN5b3UiLCJ0bHMiOiJ0bHMifQ==
    trojan://05742120-ce23-4cc8-88f5-6d221ce45bf4@fhcarm1.gaox.ml:443?allowInsecure=0#github.com%2Ffreefq%20-%20%E7%BE%8E%E5%9B%BD%20%2011
    vmess://eyJ2IjoiMiIsInBzIjoi576O5Zu9IDA1OSIsImFkZCI6ImFhLmtheWFsby5jb20iLCJwb3J0IjoiMjYyNjciLCJ0eXBlIjoibm9uZSIsImlkIjoiOTc1N2NkYmEtYzc1Yi00Yjk0LTllMzEtNzk1NmRjN2Q4NTJhIiwiYWlkIjoiMCIsIm5ldCI6IndzIiwicGF0aCI6Ii93aXMiLCJob3N0IjoiYWEua2F5YWxvLmNvbSIsInRscyI6IiJ9
    vmess://eyJ2IjoiMiIsInBzIjoi576O5Zu9IDA2NCIsImFkZCI6IjY1LjQ5LjIxNC4xODUiLCJwb3J0IjoiMzA2NTgiLCJ0eXBlIjoibm9uZSIsImlkIjoiMzUxYzY0YzEtMmY3ZC00OTAwLWEyZDItOGYwOWE2NTAxNjAzIiwiYWlkIjoiMCIsIm5ldCI6InRjcCIsInBhdGgiOiIvc3Nyc3ViIiwiaG9zdCI6InY0LnNzcnN1Yi5jb20iLCJ0bHMiOiIifQ==
    trojan://05742120-ce23-4cc8-88f5-6d221ce45bf4@fhcarm1.gaox.ml:443?allowInsecure=1#US-Openit.ml
    trojan://sharecentre@ussc.scsevers.cf:443?allowInsecure=1#US_2700%20%7C77.61Mb
    vmess://eyJ2IjoiMiIsInBzIjoiUmVsYXlfXzE1M181MU1iXzE0NiIsImFkZCI6ImFhLmtheWFsby5jb20iLCJwb3J0IjoiMjYyNjciLCJ0eXBlIjoibm9uZSIsImlkIjoiOTc1N2NkYmEtYzc1Yi00Yjk0LTllMzEtNzk1NmRjN2Q4NTJhIiwiYWlkIjoiMCIsIm5ldCI6IndzIiwicGF0aCI6Ii93aXMiLCJob3N0IjoiYWEua2F5YWxvLmNvbSIsInRscyI6IiJ9
    vmess://eyJ2IjoiMiIsInBzIjoibWF0dGtheWRpYXJ5LmNvbXznvo7lm70oVVMpVVNBL0xvc0FuZ2VsZXNfMTEiLCJhZGQiOiI0NS43Ni43MS4yMzMiLCJwb3J0IjoiNDY5ODMiLCJ0eXBlIjoibm9uZSIsImlkIjoiNjkwOTkyNTgtMTQ3Ni00NmRkLWE1MWItODRlOTE1ZTk0MWJlIiwiYWlkIjoiMCIsIm5ldCI6IndzIiwicGF0aCI6Ii8xdEdLODJsVS8iLCJob3N0IjoiIiwidGxzIjoiIn0=
    vmess://eyJ2IjoiMiIsInBzIjoiUmVsYXlf576O5Zu9LV8zOCIsImFkZCI6IjFjaHVhbi50b3AiLCJwb3J0IjoiNDQzIiwidHlwZSI6Im5vbmUiLCJpZCI6ImZhOGY5MGUwLTJmYWUtNGIwNS1kZjdhLWVhMzI1YmM1MTdkOCIsImFpZCI6IjAiLCJuZXQiOiJ3cyIsInBhdGgiOiIvZXZvIiwiaG9zdCI6IjFjaHVhbi50b3AiLCJ0bHMiOiJ0bHMifQ==
    vmess://eyJ2IjoiMiIsInBzIjoi576O5Zu9IDA2MSIsImFkZCI6InVzYS1kYWxsYXMubHZ1ZnQuY29tIiwicG9ydCI6IjQ0MyIsInR5cGUiOiJub25lIiwiaWQiOiJhYmE1MGRkNC01NDg0LTNiMDUtYjE0YS00NjYxY2FmODYyZDUiLCJhaWQiOiI0IiwibmV0Ijoid3MiLCJwYXRoIjoiL3dzIiwiaG9zdCI6InVzYS1kYWxsYXMubHZ1ZnQuY29tIiwidGxzIjoidGxzIn0=
    vmess://eyJ2IjoiMiIsInBzIjoi576O5Zu9IDA2MiIsImFkZCI6IjY3LjIxLjcyLjQxIiwicG9ydCI6IjQ0MyIsInR5cGUiOiJub25lIiwiaWQiOiIyNTY2ZDAwZi0yMThjLTQ4ZjctOWEzNi0xM2QzZDZmMWE3MjQiLCJhaWQiOiI2NCIsIm5ldCI6IndzIiwicGF0aCI6Ii9wYXRoLzE3MzQxODE0MTEyMyIsImhvc3QiOiJ3d3cuMTcwODAxMDAueHl6IiwidGxzIjoidGxzIn0=
    vmess://eyJ2IjoiMiIsInBzIjoi576O5Zu9ICA5IiwiYWRkIjoiMTUwLjIzMC40My42NSIsInBvcnQiOiIxNDU2NCIsInR5cGUiOiJub25lIiwiaWQiOiIxNTU2ZTA0MC0zMWQzLTRjNDctYjBkMi1kZGY4ODgwMTBiNGUiLCJhaWQiOiIwIiwibmV0IjoidGNwIiwicGF0aCI6Ii9obHMvY2N0djVwaGQubTN1OCIsImhvc3QiOiJ0dzI1MDMuY2xvdWRtYXRyaXgueHl6IiwidGxzIjoiIn0=
    vmess://eyJ2IjoiMiIsInBzIjoi576O5Zu9IDA3MCIsImFkZCI6IjE1MC4yMzAuNDMuNjUiLCJwb3J0IjoiMTQ1NjQiLCJ0eXBlIjoibm9uZSIsImlkIjoiMTU1NmUwNDAtMzFkMy00YzQ3LWIwZDItZGRmODg4MDEwYjRlIiwiYWlkIjoiMCIsIm5ldCI6InRjcCIsInBhdGgiOiIvZWlzYXNxYSIsImhvc3QiOiIiLCJ0bHMiOiIifQ==
    vmess://eyJ2IjoiMiIsInBzIjoi576O5Zu9IDA4MCIsImFkZCI6IjE1MC4yMzAuNDMuNjUiLCJwb3J0IjoiMTQ1NjQiLCJ0eXBlIjoibm9uZSIsImlkIjoiMTU1NmUwNDAtMzFkMy00YzQ3LWIwZDItZGRmODg4MDEwYjRlIiwiYWlkIjoiMCIsIm5ldCI6InRjcCIsInBhdGgiOiIvIiwiaG9zdCI6IiIsInRscyI6IiJ9
    vmess://eyJ2IjoiMiIsInBzIjoiVVNfMzU1OSIsImFkZCI6IjE1MC4yMzAuNDMuNjUiLCJwb3J0IjoiMTQ1NjQiLCJ0eXBlIjoibm9uZSIsImlkIjoiMTU1NmUwNDAtMzFkMy00YzQ3LWIwZDItZGRmODg4MDEwYjRlIiwiYWlkIjoiMCIsIm5ldCI6InRjcCIsInBhdGgiOiIvZXZvIiwiaG9zdCI6IiIsInRscyI6IiJ9
    vmess://eyJ2IjoiMiIsInBzIjoiVVNfMjU0MCB8NzMuODBNYiIsImFkZCI6ImFhLmtheWFsby5jb20iLCJwb3J0IjoiMjYyNjciLCJ0eXBlIjoibm9uZSIsImlkIjoiOTc1N2NkYmEtYzc1Yi00Yjk0LTllMzEtNzk1NmRjN2Q4NTJhIiwiYWlkIjoiMCIsIm5ldCI6IndzIiwicGF0aCI6Ii93aXMiLCJob3N0IjoiYWEua2F5YWxvLmNvbSIsInRscyI6IiJ9
    vmess://eyJ2IjoiMiIsInBzIjoiXzcwOSIsImFkZCI6InVzYS1kYWxsYXMubHZ1ZnQuY29tIiwicG9ydCI6IjQ0MyIsInR5cGUiOiJub25lIiwiaWQiOiJhYmE1MGRkNC01NDg0LTNiMDUtYjE0YS00NjYxY2FmODYyZDUiLCJhaWQiOiI0IiwibmV0Ijoid3MiLCJwYXRoIjoiL3dzIiwiaG9zdCI6InVzYS1kYWxsYXMubHZ1ZnQuY29tIiwidGxzIjoidGxzIn0=
    vmess://eyJ2IjoiMiIsInBzIjoi576O5Zu9IiwiYWRkIjoiMTUwLjIzMC40My42NSIsInBvcnQiOiIxNDU2NCIsInR5cGUiOiJub25lIiwiaWQiOiIxNTU2ZTA0MC0zMWQzLTRjNDctYjBkMi1kZGY4ODgwMTBiNGUiLCJhaWQiOiIwIiwibmV0IjoidGNwIiwicGF0aCI6Ii8iLCJob3N0IjoiMTUwLjIzMC40My42NSIsInRscyI6IiJ9
    vmess://eyJ2IjoiMiIsInBzIjoiXzE2OV8wMU1iXzEwIiwiYWRkIjoiMTUwLjIzMC40My42NSIsInBvcnQiOiIxNDU2NCIsInR5cGUiOiJub25lIiwiaWQiOiIxNTU2ZTA0MC0zMWQzLTRjNDctYjBkMi1kZGY4ODgwMTBiNGUiLCJhaWQiOiIwIiwibmV0IjoidGNwIiwicGF0aCI6Ii9obHMvY2N0djVwaGQubTN1OCIsImhvc3QiOiIiLCJ0bHMiOiIifQ==
    vmess://eyJ2IjoiMiIsInBzIjoiVVMtT3Blbml0Lm1sIiwiYWRkIjoiYWEua2F5YWxvLmNvbSIsInBvcnQiOiIyNjI2NyIsInR5cGUiOiJub25lIiwiaWQiOiI5NzU3Y2RiYS1jNzViLTRiOTQtOWUzMS03OTU2ZGM3ZDg1MmEiLCJhaWQiOiIwIiwibmV0Ijoid3MiLCJwYXRoIjoiL3dpcyIsImhvc3QiOiJhYS5rYXlhbG8uY29tIiwidGxzIjoiIn0=
    vmess://eyJ2IjoiMiIsInBzIjoi576O5Zu9IiwiYWRkIjoiYWEua2F5YWxvLmNvbSIsInBvcnQiOiIyNjI2NyIsInR5cGUiOiJub25lIiwiaWQiOiI5NzU3Y2RiYS1jNzViLTRiOTQtOWUzMS03OTU2ZGM3ZDg1MmEiLCJhaWQiOiIwIiwibmV0Ijoid3MiLCJwYXRoIjoiL3dpcyIsImhvc3QiOiJhYS5rYXlhbG8uY29tIiwidGxzIjoiIn0=
    vmess://eyJ2IjoiMiIsInBzIjoi576O5Zu9IDA0OCIsImFkZCI6Imllc2VpMWVpLmNvbSIsInBvcnQiOiI0NDMiLCJ0eXBlIjoibm9uZSIsImlkIjoiYWJhNTBkZDQtNTQ4NC0zYjA1LWIxNGEtNDY2MWNhZjg2MmQ1IiwiYWlkIjoiNCIsIm5ldCI6IndzIiwicGF0aCI6Ii93cyIsImhvc3QiOiJpZXNlaTFlaS5jb20iLCJ0bHMiOiJ0bHMifQ==
    vmess://eyJ2IjoiMiIsInBzIjoiUmVsYXlf576O5Zu9LV8zNzQzIiwiYWRkIjoiYWEua2F5YWxvLmNvbSIsInBvcnQiOiIyNjI2NyIsInR5cGUiOiJub25lIiwiaWQiOiI5NzU3Y2RiYS1jNzViLTRiOTQtOWUzMS03OTU2ZGM3ZDg1MmEiLCJhaWQiOiIwIiwibmV0Ijoid3MiLCJwYXRoIjoiL3dpcyIsImhvc3QiOiJhYS5rYXlhbG8uY29tIiwidGxzIjoiIn0=
    vmess://eyJ2IjoiMiIsInBzIjoiVVMtT3Blbml0Lm1sIiwiYWRkIjoiMTUwLjIzMC40My42NSIsInBvcnQiOiIxNDU2NCIsInR5cGUiOiJub25lIiwiaWQiOiIxNTU2ZTA0MC0zMWQzLTRjNDctYjBkMi1kZGY4ODgwMTBiNGUiLCJhaWQiOiIwIiwibmV0IjoidGNwIiwicGF0aCI6Ii93cyIsImhvc3QiOiIxNTQuOTQuMjE0LjIiLCJ0bHMiOiIifQ==
    vmess://eyJ2IjoiMiIsInBzIjoiVVMtT3Blbml0Lm1sIiwiYWRkIjoiYWEua2F5YWxvLmNvbSIsInBvcnQiOiIyNjI2NyIsInR5cGUiOiJub25lIiwiaWQiOiI5NzU3Y2RiYS1jNzViLTRiOTQtOWUzMS03OTU2ZGM3ZDg1MmEiLCJhaWQiOiIwIiwibmV0Ijoid3MiLCJwYXRoIjoiL3dpcyIsImhvc3QiOiJhYS5rYXlhbG8uY29tIiwidGxzIjoiIn0=
    trojan://sharecentre@ussc.scsevers.cf:443?allowInsecure=1#US_2557%20%7C62.46Mb
    vmess://eyJ2IjoiMiIsInBzIjoi576O5Zu9IDA1NCIsImFkZCI6IjIwOC45OC40OC4yIiwicG9ydCI6IjQ0MyIsInR5cGUiOiJub25lIiwiaWQiOiJhYmE1MGRkNC01NDg0LTNiMDUtYjE0YS00NjYxY2FmODYyZDUiLCJhaWQiOiI0IiwibmV0Ijoid3MiLCJwYXRoIjoiL3dzIiwiaG9zdCI6Imllc2VpMWVpLmNvbSIsInRscyI6InRscyJ9
    vmess://eyJ2IjoiMiIsInBzIjoiVVMtT3Blbml0Lm1sIiwiYWRkIjoiYWEua2F5YWxvLmNvbSIsInBvcnQiOiIyNjI2NyIsInR5cGUiOiJub25lIiwiaWQiOiI5NzU3Y2RiYS1jNzViLTRiOTQtOWUzMS03OTU2ZGM3ZDg1MmEiLCJhaWQiOiIwIiwibmV0Ijoid3MiLCJwYXRoIjoiL3dpcyIsImhvc3QiOiJhYS5rYXlhbG8uY29tIiwidGxzIjoiIn0=
    vmess://eyJ2IjoiMiIsInBzIjoi576O5Zu9IiwiYWRkIjoidmZseTUueHl6IiwicG9ydCI6IjQ0MyIsInR5cGUiOiJub25lIiwiaWQiOiI4MjUxMzZiYi1mYzBhLTRmNDMtODMwNy1kYzJlMzZmMjdlMmQiLCJhaWQiOiIwIiwibmV0Ijoid3MiLCJwYXRoIjoiL215YmxvZyIsImhvc3QiOiJ2Zmx5NS54eXoiLCJ0bHMiOiJ0bHMifQ==
    vmess://eyJ2IjoiMiIsInBzIjoiZ2l0aHViLmNvbS9mcmVlZnEgLSDnvo7lm70gIDMwIiwiYWRkIjoic2FuZnJhbmNpc2NvbGFmYXlldHRlLmNsdWIiLCJwb3J0IjoiNDQzIiwidHlwZSI6Im5vbmUiLCJpZCI6ImNjMGI0NDY5LWMwZTUtNGVmYi04ZjY5LWE2ZGY2NGRiMjRlZSIsImFpZCI6IjAiLCJuZXQiOiJ3cyIsInBhdGgiOiIvbmV1cm9tYW5jZXIiLCJob3N0Ijoic2FuZnJhbmNpc2NvbGFmYXlldHRlLmNsdWIiLCJ0bHMiOiJ0bHMifQ==
    vmess://eyJ2IjoiMiIsInBzIjoi6L+Z5Lqb6IqC54K55Y+q6IO95aSH55So5oiW6ICF6Ziy5q2i5aSx6IGU77yM6Jm954S26LSo6YeP5bm25LiN5piv5b6I5aW977yM5Lmf6K+35L2O6LCD5L2/55SoOikiLCJhZGQiOiI0NS43Ni43MS4yMzMiLCJwb3J0IjoiNDY5ODMiLCJ0eXBlIjoibm9uZSIsImlkIjoiNjkwOTkyNTgtMTQ3Ni00NmRkLWE1MWItODRlOTE1ZTk0MWJlIiwiYWlkIjoiMCIsIm5ldCI6IndzIiwicGF0aCI6Ii8xdEdLODJsVS8iLCJob3N0IjoiNDUuNzYuNzEuMjMzIiwidGxzIjoiIn0=
    trojan://05742120-ce23-4cc8-88f5-6d221ce45bf4@fhcarm1.gaox.ml:443?allowInsecure=1#US_2702%20%7C87.65Mb
    vmess://eyJ2IjoiMiIsInBzIjoiUmVsYXlfXzE1M181MU1iXzE0NiIsImFkZCI6ImFhLmtheWFsby5jb20iLCJwb3J0IjoiMjYyNjciLCJ0eXBlIjoibm9uZSIsImlkIjoiOTc1N2NkYmEtYzc1Yi00Yjk0LTllMzEtNzk1NmRjN2Q4NTJhIiwiYWlkIjoiMCIsIm5ldCI6IndzIiwicGF0aCI6Ii93aXMiLCJob3N0IjoiYWEua2F5YWxvLmNvbSIsInRscyI6IiJ9
    vmess://eyJ2IjoiMiIsInBzIjoiVVNfMjU0MyB8MzIuNjhNYiIsImFkZCI6InVzYS1kYWxsYXMubHZ1ZnQuY29tIiwicG9ydCI6IjQ0MyIsInR5cGUiOiJub25lIiwiaWQiOiJhYmE1MGRkNC01NDg0LTNiMDUtYjE0YS00NjYxY2FmODYyZDUiLCJhaWQiOiI0IiwibmV0Ijoid3MiLCJwYXRoIjoiL3dzIiwiaG9zdCI6InVzYS1kYWxsYXMubHZ1ZnQuY29tIiwidGxzIjoidGxzIn0=
    vmess://eyJ2IjoiMiIsInBzIjoi576O5Zu9IDA1NyIsImFkZCI6IjE4NS4yMDIuMTcyLjI0MyIsInBvcnQiOiI0MDk0MSIsInR5cGUiOiJub25lIiwiaWQiOiI0ODUzNzgyMC0xNGYzLTRkZTctZDI2ZS1hM2I4OGJjZjAxNWEiLCJhaWQiOiIwIiwibmV0IjoidGNwIiwicGF0aCI6Ii9uZXVyb21hbmNlciIsImhvc3QiOiJzYW5mcmFuY2lzY29sYWZheWV0dGUuY2x1YiIsInRscyI6IiJ9
    vmess://eyJ2IjoiMiIsInBzIjoi576O5Zu9XzI2NTUiLCJhZGQiOiIxODUuMjAyLjE3Mi4yNDMiLCJwb3J0IjoiNDA5NDEiLCJ0eXBlIjoibm9uZSIsImlkIjoiNDg1Mzc4MjAtMTRmMy00ZGU3LWQyNmUtYTNiODhiY2YwMTVhIiwiYWlkIjoiMCIsIm5ldCI6InRjcCIsInBhdGgiOiIvIiwiaG9zdCI6IiIsInRscyI6IiJ9
    vmess://eyJ2IjoiMiIsInBzIjoiVVMiLCJhZGQiOiIxODUuMjAyLjE3Mi4yNDMiLCJwb3J0IjoiNDA5NDEiLCJ0eXBlIjoibm9uZSIsImlkIjoiNDg1Mzc4MjAtMTRmMy00ZGU3LWQyNmUtYTNiODhiY2YwMTVhIiwiYWlkIjoiMCIsIm5ldCI6InRjcCIsInBhdGgiOiIvIiwiaG9zdCI6IjE0NC4zNC4yNDguMjYiLCJ0bHMiOiIifQ==
    vmess://eyJ2IjoiMiIsInBzIjoiVVNfMjY0OSB8NzcuMjhNYiIsImFkZCI6Imllc2VpMWVpLmNvbSIsInBvcnQiOiI0NDMiLCJ0eXBlIjoibm9uZSIsImlkIjoiYWJhNTBkZDQtNTQ4NC0zYjA1LWIxNGEtNDY2MWNhZjg2MmQ1IiwiYWlkIjoiNCIsIm5ldCI6IndzIiwicGF0aCI6Ii93cyIsImhvc3QiOiJpZXNlaTFlaS5jb20iLCJ0bHMiOiJ0bHMifQ==
    vmess://eyJ2IjoiMiIsInBzIjoiVVMtT3Blbml0Lm1sIiwiYWRkIjoiMTg1LjIwMi4xNzIuMjQzIiwicG9ydCI6IjQwOTQxIiwidHlwZSI6Im5vbmUiLCJpZCI6IjQ4NTM3ODIwLTE0ZjMtNGRlNy1kMjZlLWEzYjg4YmNmMDE1YSIsImFpZCI6IjAiLCJuZXQiOiJ0Y3AiLCJwYXRoIjoiL3dzIiwiaG9zdCI6IjE1NC45NC4yMTQuMiIsInRscyI6IiJ9
    vmess://eyJ2IjoiMiIsInBzIjoiVVNfMjY2MiB8MTI5LjgwTWIiLCJhZGQiOiJ1c2EtZGFsbGFzLmx2dWZ0LmNvbSIsInBvcnQiOiI0NDMiLCJ0eXBlIjoibm9uZSIsImlkIjoiYWJhNTBkZDQtNTQ4NC0zYjA1LWIxNGEtNDY2MWNhZjg2MmQ1IiwiYWlkIjoiNCIsIm5ldCI6IndzIiwicGF0aCI6Ii93cyIsImhvc3QiOiJ1c2EtZGFsbGFzLmx2dWZ0LmNvbSIsInRscyI6InRscyJ9
    vmess://eyJ2IjoiMiIsInBzIjoiZ2l0aHViLmNvbS9mcmVlZnEgLSDnvo7lm71DbG91ZEZsYXJl6IqC54K5IDM4IiwiYWRkIjoidXMwMi5nb2dvZ29vLmN5b3UiLCJwb3J0IjoiNDQzIiwidHlwZSI6Im5vbmUiLCJpZCI6ImRiNWQxYWEzLTkwOGItNDRkMS1iZTBhLTRlNmE4ZDRlNGNkYSIsImFpZCI6IjAiLCJuZXQiOiJ3cyIsInBhdGgiOiIvZ28iLCJob3N0IjoidXMwMi5nb2dvZ29vLmN5b3UiLCJ0bHMiOiJ0bHMifQ==
    vmess://eyJ2IjoiMiIsInBzIjoiVVMtT3Blbml0Lm1sIiwiYWRkIjoic2FuZnJhbmNpc2NvbGFmYXlldHRlLmNsdWIiLCJwb3J0IjoiNDQzIiwidHlwZSI6Im5vbmUiLCJpZCI6ImNjMGI0NDY5LWMwZTUtNGVmYi04ZjY5LWE2ZGY2NGRiMjRlZSIsImFpZCI6IjAiLCJuZXQiOiJ3cyIsInBhdGgiOiIvbmV1cm9tYW5jZXIiLCJob3N0Ijoic2FuZnJhbmNpc2NvbGFmYXlldHRlLmNsdWIiLCJ0bHMiOiJ0bHMifQ==
    vmess://eyJ2IjoiMiIsInBzIjoi6L+Z5Lqb6IqC54K55Y+q6IO95aSH55So5oiW6ICF6Ziy5q2i5aSx6IGU77yM6Jm954S26LSo6YeP5bm25LiN5piv5b6I5aW977yM5Lmf6K+35L2O6LCD5L2/55SoOikiLCJhZGQiOiI2NS40OS4yMTQuMTg1IiwicG9ydCI6IjMwNjU4IiwidHlwZSI6Im5vbmUiLCJpZCI6IjM1MWM2NGMxLTJmN2QtNDkwMC1hMmQyLThmMDlhNjUwMTYwMyIsImFpZCI6IjAiLCJuZXQiOiJ0Y3AiLCJwYXRoIjoiLyIsImhvc3QiOiI2NS40OS4yMTQuMTg1IiwidGxzIjoiIn0=
    vmess://eyJ2IjoiMiIsInBzIjoi576O5Zu9IDA2OCIsImFkZCI6ImFhLmtheWFsby5jb20iLCJwb3J0IjoiMjYyNjciLCJ0eXBlIjoibm9uZSIsImlkIjoiOTc1N2NkYmEtYzc1Yi00Yjk0LTllMzEtNzk1NmRjN2Q4NTJhIiwiYWlkIjoiMCIsIm5ldCI6IndzIiwicGF0aCI6Ii93aXMiLCJob3N0IjoiYWEua2F5YWxvLmNvbSIsInRscyI6IiJ9
    trojan://f39bd244-f5fe-415c-8b98-a1e5250bf178@fhcarm2.gaox.ml:443?allowInsecure=0#github.com%2Ffreefq%20-%20%E7%BE%8E%E5%9B%BD%20%2039
    vmess://eyJ2IjoiMiIsInBzIjoiVVMiLCJhZGQiOiIxODUuMjAyLjE3Mi4yNDMiLCJwb3J0IjoiNDA5NDEiLCJ0eXBlIjoibm9uZSIsImlkIjoiNDg1Mzc4MjAtMTRmMy00ZGU3LWQyNmUtYTNiODhiY2YwMTVhIiwiYWlkIjoiMCIsIm5ldCI6InRjcCIsInBhdGgiOiIvd3MiLCJob3N0IjoiNDUuMzUuODQuMTYyIiwidGxzIjoiIn0=
    vmess://eyJ2IjoiMiIsInBzIjoi576O5Zu9IDA1OCIsImFkZCI6IjE4NS4yMDIuMTcyLjI0MyIsInBvcnQiOiI0MDk0MSIsInR5cGUiOiJub25lIiwiaWQiOiI0ODUzNzgyMC0xNGYzLTRkZTctZDI2ZS1hM2I4OGJjZjAxNWEiLCJhaWQiOiIwIiwibmV0IjoidGNwIiwicGF0aCI6Ii93cyIsImhvc3QiOiJsdnVmdC5jb20iLCJ0bHMiOiIifQ==
    vmess://eyJ2IjoiMiIsInBzIjoiVVMt6auY6YCf6IqC54K56LSt5Lmw77yadjEubWsvdmlw77yI5rWP6KeI5Zmo5omT5byA77yJIiwiYWRkIjoidXMzLjMxdnBuLmNvbSIsInBvcnQiOiI0NDMiLCJ0eXBlIjoibm9uZSIsImlkIjoiMmVmNjRkYzgtY2EzYy00NWI4LWFkNWYtMjA4NzE0NTIxNDNiIiwiYWlkIjoiMCIsIm5ldCI6IndzIiwicGF0aCI6Ii9mYXN0c3NoLzMxMDI2Mzc0OTNxcWNvbS82MjZjZjdkOGJkNDliLyIsImhvc3QiOiJ1czMuMzF2cG4uY29tIiwidGxzIjoidGxzIn0=
    vmess://eyJ2IjoiMiIsInBzIjoi6L+Z5Lqb6IqC54K55Y+q6IO95aSH55So5oiW6ICF6Ziy5q2i5aSx6IGU77yM6Jm954S26LSo6YeP5bm25LiN5piv5b6I5aW977yM5Lmf6K+35L2O6LCD5L2/55SoOikiLCJhZGQiOiI0NS43Ni43MS4yMzMiLCJwb3J0IjoiNDY5ODMiLCJ0eXBlIjoibm9uZSIsImlkIjoiNjkwOTkyNTgtMTQ3Ni00NmRkLWE1MWItODRlOTE1ZTk0MWJlIiwiYWlkIjoiMCIsIm5ldCI6IndzIiwicGF0aCI6Ii8xdEdLODJsVS8iLCJob3N0IjoiNDUuNzYuNzEuMjMzIiwidGxzIjoiIn0=
    vmess://eyJ2IjoiMiIsInBzIjoi576O5Zu9IDAxMyIsImFkZCI6InVzMDIuZ29nb2dvby5jeW91IiwicG9ydCI6IjQ0MyIsInR5cGUiOiJub25lIiwiaWQiOiJkYjVkMWFhMy05MDhiLTQ0ZDEtYmUwYS00ZTZhOGQ0ZTRjZGEiLCJhaWQiOiIwIiwibmV0Ijoid3MiLCJwYXRoIjoiL2dvIiwiaG9zdCI6InVzMDIuZ29nb2dvby5jeW91IiwidGxzIjoidGxzIn0=
    trojan://sharecentre@ussc.scsevers.cf:443?allowInsecure=1#US_2629%20%7C65.23Mb
    vmess://eyJ2IjoiMiIsInBzIjoiUmVsYXlfXzE1M181MU1iXzE0NiIsImFkZCI6ImFhLmtheWFsby5jb20iLCJwb3J0IjoiMjYyNjciLCJ0eXBlIjoibm9uZSIsImlkIjoiOTc1N2NkYmEtYzc1Yi00Yjk0LTllMzEtNzk1NmRjN2Q4NTJhIiwiYWlkIjoiMCIsIm5ldCI6IndzIiwicGF0aCI6Ii93aXMiLCJob3N0IjoiYWEua2F5YWxvLmNvbSIsInRscyI6IiJ9
    trojan://e23f408a-012e-4030-8b31-02022031cb50@fhcamd1.gaox.ml:443?allowInsecure=0#github.com%2Fv2rayfree%20-%20%E7%BE%8E%E5%9B%BD%E4%BA%9A%E5%88%A9%E6%A1%91%E9%82%A3%E5%B7%9E%E5%87%A4%E5%87%B0%E5%9F%8EOracle%E4%BA%91%E8%AE%A1%E7%AE%97%E6%95%B0%E6%8D%AE%E4%B8%AD%E5%BF%83%2025
    vmess://eyJ2IjoiMiIsInBzIjoiVVMtT3Blbml0Lm1sIiwiYWRkIjoidXNhLXdhc2hpbmd0b24ubHZ1ZnQuY29tIiwicG9ydCI6IjQ0MyIsInR5cGUiOiJub25lIiwiaWQiOiJhYmE1MGRkNC01NDg0LTNiMDUtYjE0YS00NjYxY2FmODYyZDUiLCJhaWQiOiI0IiwibmV0Ijoid3MiLCJwYXRoIjoiL3dzIiwiaG9zdCI6InVzYS13YXNoaW5ndG9uLmx2dWZ0LmNvbSIsInRscyI6InRscyJ9
    vmess://eyJ2IjoiMiIsInBzIjoi576O5Zu9IDA2MiIsImFkZCI6IjY3LjIxLjcyLjQxIiwicG9ydCI6IjQ0MyIsInR5cGUiOiJub25lIiwiaWQiOiIyNTY2ZDAwZi0yMThjLTQ4ZjctOWEzNi0xM2QzZDZmMWE3MjQiLCJhaWQiOiI2NCIsIm5ldCI6IndzIiwicGF0aCI6Ii9wYXRoLzE3MzQxODE0MTEyMyIsImhvc3QiOiJ3d3cuMTcwODAxMDAueHl6IiwidGxzIjoidGxzIn0=
    vmess://eyJ2IjoiMiIsInBzIjoiVVMtT3Blbml0Lm1sIiwiYWRkIjoiYWEua2F5YWxvLmNvbSIsInBvcnQiOiIyNjI2NyIsInR5cGUiOiJub25lIiwiaWQiOiI5NzU3Y2RiYS1jNzViLTRiOTQtOWUzMS03OTU2ZGM3ZDg1MmEiLCJhaWQiOiIwIiwibmV0Ijoid3MiLCJwYXRoIjoiL3dpcyIsImhvc3QiOiJhYS5rYXlhbG8uY29tIiwidGxzIjoiIn0=
    vmess://eyJ2IjoiMiIsInBzIjoi576O5Zu9IDA0MyIsImFkZCI6IjE5Mi4xODYuMTI5LjY2IiwicG9ydCI6IjQ0MyIsInR5cGUiOiJub25lIiwiaWQiOiJhYmE1MGRkNC01NDg0LTNiMDUtYjE0YS00NjYxY2FmODYyZDUiLCJhaWQiOiI0IiwibmV0Ijoid3MiLCJwYXRoIjoiL3dzIiwiaG9zdCI6InVzYS1idWZmYWxvLmx2dWZ0LmNvbSIsInRscyI6InRscyJ9
    vmess://eyJ2IjoiMiIsInBzIjoiUmVsYXlf576O5Zu9LV8yMjQ3IiwiYWRkIjoiMTkyLjk2LjIwNC4yNTAiLCJwb3J0IjoiNDQzIiwidHlwZSI6Im5vbmUiLCJpZCI6ImFiYTUwZGQ0LTU0ODQtM2IwNS1iMTRhLTQ2NjFjYWY4NjJkNSIsImFpZCI6IjQiLCJuZXQiOiJ3cyIsInBhdGgiOiIvd3MiLCJob3N0IjoidXNhLXdhc2hpbmd0b24ubHZ1ZnQuY29tIiwidGxzIjoidGxzIn0=
    vmess://eyJ2IjoiMiIsInBzIjoiUmVsYXlf576O5Zu9LV8yMjQ3IiwiYWRkIjoiMTkyLjk2LjIwNC4yNTAiLCJwb3J0IjoiNDQzIiwidHlwZSI6Im5vbmUiLCJpZCI6ImFiYTUwZGQ0LTU0ODQtM2IwNS1iMTRhLTQ2NjFjYWY4NjJkNSIsImFpZCI6IjQiLCJuZXQiOiJ3cyIsInBhdGgiOiIvd3MiLCJob3N0IjoidXNhLXdhc2hpbmd0b24ubHZ1ZnQuY29tIiwidGxzIjoidGxzIn0=
    vmess://eyJ2IjoiMiIsInBzIjoiZ2l0aHViLmNvbS9mcmVlZnEgLSDnvo7lm73nur3nuqbluIJEaWdpdGFsT2NlYW7kupHlhazlj7ggNTMiLCJhZGQiOiJ1czMuMzF2cG4uY29tIiwicG9ydCI6IjQ0MyIsInR5cGUiOiJub25lIiwiaWQiOiIyZWY2NGRjOC1jYTNjLTQ1YjgtYWQ1Zi0yMDg3MTQ1MjE0M2IiLCJhaWQiOiIwIiwibmV0Ijoid3MiLCJwYXRoIjoiL2Zhc3Rzc2gvMzEwMjYzNzQ5M3FxY29tLzYyNmNmN2Q4YmQ0OWIvIiwiaG9zdCI6InVzMy4zMXZwbi5jb20iLCJ0bHMiOiJ0bHMifQ==
    vmess://eyJ2IjoiMiIsInBzIjoi576O5Zu9IDA2MCIsImFkZCI6InVzYS13YXNoaW5ndG9uLmx2dWZ0LmNvbSIsInBvcnQiOiI0NDMiLCJ0eXBlIjoibm9uZSIsImlkIjoiYWJhNTBkZDQtNTQ4NC0zYjA1LWIxNGEtNDY2MWNhZjg2MmQ1IiwiYWlkIjoiNCIsIm5ldCI6IndzIiwicGF0aCI6Ii93cyIsImhvc3QiOiJ1c2Etd2FzaGluZ3Rvbi5sdnVmdC5jb20iLCJ0bHMiOiJ0bHMifQ==
    vmess://eyJ2IjoiMiIsInBzIjoiVVNfMjY2MiB8MTI5LjgwTWIiLCJhZGQiOiJ1c2EtZGFsbGFzLmx2dWZ0LmNvbSIsInBvcnQiOiI0NDMiLCJ0eXBlIjoibm9uZSIsImlkIjoiYWJhNTBkZDQtNTQ4NC0zYjA1LWIxNGEtNDY2MWNhZjg2MmQ1IiwiYWlkIjoiNCIsIm5ldCI6IndzIiwicGF0aCI6Ii93cyIsImhvc3QiOiJ1c2EtZGFsbGFzLmx2dWZ0LmNvbSIsInRscyI6InRscyJ9
    vmess://eyJ2IjoiMiIsInBzIjoi576O5Zu9IDA1NSIsImFkZCI6IjE5Mi45Ni4yMDQuMjUwIiwicG9ydCI6IjQ0MyIsInR5cGUiOiJub25lIiwiaWQiOiJhYmE1MGRkNC01NDg0LTNiMDUtYjE0YS00NjYxY2FmODYyZDUiLCJhaWQiOiI0IiwibmV0Ijoid3MiLCJwYXRoIjoiL3dzIiwiaG9zdCI6InVzYS13YXNoaW5ndG9uLmx2dWZ0LmNvbSIsInRscyI6InRscyJ9
    vmess://eyJ2IjoiMiIsInBzIjoiZ2l0aHViLmNvbS92MnJheWZyZWUgLSDnvo7lm73nur3nuqbluIJEaWdpdGFsT2NlYW7kupHlhazlj7ggNTMiLCJhZGQiOiJ1czMuMzF2cG4uY29tIiwicG9ydCI6IjQ0MyIsInR5cGUiOiJub25lIiwiaWQiOiIyZWY2NGRjOC1jYTNjLTQ1YjgtYWQ1Zi0yMDg3MTQ1MjE0M2IiLCJhaWQiOiIwIiwibmV0Ijoid3MiLCJwYXRoIjoiL2Zhc3Rzc2gvMzEwMjYzNzQ5M3FxY29tLzYyNmNmN2Q4YmQ0OWIvIiwiaG9zdCI6InVzMy4zMXZwbi5jb20iLCJ0bHMiOiJ0bHMifQ==
    vmess://eyJ2IjoiMiIsInBzIjoi576O5Zu9IDA0MiIsImFkZCI6InVzYS1idWZmYWxvLmx2dWZ0LmNvbSIsInBvcnQiOiI0NDMiLCJ0eXBlIjoibm9uZSIsImlkIjoiYWJhNTBkZDQtNTQ4NC0zYjA1LWIxNGEtNDY2MWNhZjg2MmQ1IiwiYWlkIjoiNCIsIm5ldCI6IndzIiwicGF0aCI6Ii93cyIsImhvc3QiOiJ1c2EtYnVmZmFsby5sdnVmdC5jb20iLCJ0bHMiOiJ0bHMifQ==
    vmess://eyJ2IjoiMiIsInBzIjoi576O5Zu9IiwiYWRkIjoiMTg1LjIwMi4xNzIuMjQzIiwicG9ydCI6IjQwOTQxIiwidHlwZSI6Im5vbmUiLCJpZCI6IjQ4NTM3ODIwLTE0ZjMtNGRlNy1kMjZlLWEzYjg4YmNmMDE1YSIsImFpZCI6IjAiLCJuZXQiOiJ0Y3AiLCJwYXRoIjoiLyIsImhvc3QiOiIxODUuMjAyLjE3Mi4yNDMiLCJ0bHMiOiIifQ==
    vmess://eyJ2IjoiMiIsInBzIjoiZ2l0aHViLmNvbS9mcmVlZnEgLSDnvo7lm73nur3nuqbluIJEaWdpdGFsT2NlYW7kupHlhazlj7ggNTMiLCJhZGQiOiJ1czMuMzF2cG4uY29tIiwicG9ydCI6IjQ0MyIsInR5cGUiOiJub25lIiwiaWQiOiIyZWY2NGRjOC1jYTNjLTQ1YjgtYWQ1Zi0yMDg3MTQ1MjE0M2IiLCJhaWQiOiIwIiwibmV0Ijoid3MiLCJwYXRoIjoiL2Zhc3Rzc2gvMzEwMjYzNzQ5M3FxY29tLzYyNmNmN2Q4YmQ0OWIvIiwiaG9zdCI6InVzMy4zMXZwbi5jb20iLCJ0bHMiOiJ0bHMifQ==
    vmess://eyJ2IjoiMiIsInBzIjoiVVNfMjY3MyB8MTUxLjUzTWIiLCJhZGQiOiJ1c2Etd2FzaGluZ3Rvbi5sdnVmdC5jb20iLCJwb3J0IjoiNDQzIiwidHlwZSI6Im5vbmUiLCJpZCI6ImFiYTUwZGQ0LTU0ODQtM2IwNS1iMTRhLTQ2NjFjYWY4NjJkNSIsImFpZCI6IjQiLCJuZXQiOiJ3cyIsInBhdGgiOiIvd3MiLCJob3N0IjoidXNhLXdhc2hpbmd0b24ubHZ1ZnQuY29tIiwidGxzIjoidGxzIn0=
    vmess://eyJ2IjoiMiIsInBzIjoi6L+Z5Lqb6IqC54K55Y+q6IO95aSH55So5oiW6ICF6Ziy5q2i5aSx6IGU77yM6Jm954S26LSo6YeP5bm25LiN5piv5b6I5aW977yM5Lmf6K+35L2O6LCD5L2/55SoOikiLCJhZGQiOiJ1czMuMzF2cG4uY29tIiwicG9ydCI6IjQ0MyIsInR5cGUiOiJub25lIiwiaWQiOiIyZWY2NGRjOC1jYTNjLTQ1YjgtYWQ1Zi0yMDg3MTQ1MjE0M2IiLCJhaWQiOiIwIiwibmV0Ijoid3MiLCJwYXRoIjoiL2Zhc3Rzc2gvMzEwMjYzNzQ5M3FxY29tLzYyNmNmN2Q4YmQ0OWIvIiwiaG9zdCI6InVzMy4zMXZwbi5jb20iLCJ0bHMiOiJ0bHMifQ==
    vmess://eyJ2IjoiMiIsInBzIjoiVVMt6auY6YCf6IqC54K56LSt5Lmw77yadjEubWsvdmlw77yI5rWP6KeI5Zmo5omT5byA77yJIiwiYWRkIjoidXMwMi5nb2dvZ29vLmN5b3UiLCJwb3J0IjoiNDQzIiwidHlwZSI6Im5vbmUiLCJpZCI6ImRiNWQxYWEzLTkwOGItNDRkMS1iZTBhLTRlNmE4ZDRlNGNkYSIsImFpZCI6IjAiLCJuZXQiOiJ3cyIsInBhdGgiOiIvZ28iLCJob3N0IjoidXMwMi5nb2dvZ29vLmN5b3UiLCJ0bHMiOiJ0bHMifQ==
    vmess://eyJ2IjoiMiIsInBzIjoiVVMtT3Blbml0Lm1sIiwiYWRkIjoiYWEua2F5YWxvLmNvbSIsInBvcnQiOiIyNjI2NyIsInR5cGUiOiJub25lIiwiaWQiOiI5NzU3Y2RiYS1jNzViLTRiOTQtOWUzMS03OTU2ZGM3ZDg1MmEiLCJhaWQiOiIwIiwibmV0Ijoid3MiLCJwYXRoIjoiL3dpcyIsImhvc3QiOiJhYS5rYXlhbG8uY29tIiwidGxzIjoiIn0=
    vmess://eyJ2IjoiMiIsInBzIjoiVVMtT3Blbml0Lm1sIiwiYWRkIjoiMTg1LjIwMi4xNzIuMjQzIiwicG9ydCI6IjQwOTQxIiwidHlwZSI6Im5vbmUiLCJpZCI6IjQ4NTM3ODIwLTE0ZjMtNGRlNy1kMjZlLWEzYjg4YmNmMDE1YSIsImFpZCI6IjAiLCJuZXQiOiJ0Y3AiLCJwYXRoIjoiL3dzIiwiaG9zdCI6IjQ1LjM1Ljg0LjE2MiIsInRscyI6IiJ9
    vmess://eyJ2IjoiMiIsInBzIjoibWF0dGtheWRpYXJ5LmNvbXznvo7lm70oVVMpVVNBL0NsaWZ0b25fMTgiLCJhZGQiOiJ1czMuMzF2cG4uY29tIiwicG9ydCI6IjQ0MyIsInR5cGUiOiJub25lIiwiaWQiOiIyZWY2NGRjOC1jYTNjLTQ1YjgtYWQ1Zi0yMDg3MTQ1MjE0M2IiLCJhaWQiOiIwIiwibmV0Ijoid3MiLCJwYXRoIjoiL2Zhc3Rzc2gvMzEwMjYzNzQ5M3FxY29tLzYyNmNmN2Q4YmQ0OWIvIiwiaG9zdCI6InVzMy4zMXZwbi5jb20iLCJ0bHMiOiJ0bHMifQ==
    vmess://eyJ2IjoiMiIsInBzIjoiVVNfMjYxMiIsImFkZCI6IjE4NS4yMDIuMTcyLjI0MyIsInBvcnQiOiI0MDk0MSIsInR5cGUiOiJub25lIiwiaWQiOiI0ODUzNzgyMC0xNGYzLTRkZTctZDI2ZS1hM2I4OGJjZjAxNWEiLCJhaWQiOiIwIiwibmV0IjoidGNwIiwicGF0aCI6Ii93cyIsImhvc3QiOiIiLCJ0bHMiOiIifQ==

</details>

### 所有节点
合并节点总数: `6047`
[节点链接](https://raw.githubusercontent.com/alanbobs999/TopFreeProxies/master/sub/sub_merge.txt)

### 节点来源
- [pojiezhiyuanjun/freev2](https://github.com/pojiezhiyuanjun/freev2), 节点数量: `73`
- [chfchf0306/clash](https://github.com/chfchf0306/clash), 节点数量: `498`
- [xiyaowong/freeFQ](https://github.com/xiyaowong/freeFQ), 节点数量: `156`
- [freefq/free](https://github.com/freefq/free), 节点数量: `55`
- [learnhard-cn/free_proxy_ss](https://github.com/learnhard-cn/free_proxy_ss), 节点数量: `181`
- [vpei/Free-Node-Merge](https://github.com/vpei/Free-Node-Merge), 节点数量: `100`
- [colatiger/v2ray-nodes](https://github.com/colatiger/v2ray-nodes), 节点数量: `47`
- [oslook/clash-freenode](https://github.com/oslook/clash-freenode), 节点数量: `42`
- [ssrsub/ssr](https://github.com/ssrsub/ssr), 节点数量: `35`
- [Leon406/SubCrawler](https://github.com/Leon406/SubCrawler), 节点数量: `2445`
- [yu-steven/openit](https://github.com/yu-steven/openit), 节点数量: `204`
- [alanbobs999/TopFreeProxies](https://github.com/alanbobs999/TopFreeProxies), 节点数量: `99`
- [ldir92664/Vmess-Actions](https://github.com/ldir92664/Vmess-Actions), 节点数量: `83`
- [gooooooooooooogle/Clash-Config](https://github.com/gooooooooooooogle/Clash-Config), 节点数量: `42`
- [Jsnzkpg/Jsnzkpg](https://github.com/Jsnzkpg/Jsnzkpg), 节点数量: `132`
- [ermaozi/get_subscribe](https://github.com/ermaozi/get_subscribe), 节点数量: `145`
- [wrfree/free](https://github.com/wrfree/free), 节点数量: `55`
- [GreenFishStudio/GreenFish](https://github.com/GreenFishStudio/GreenFish), 节点数量: `62`
- [ObcbO/auto-subscribe](https://github.com/ObcbO/auto-subscribe), 节点数量: `0`
- [tomdegnan/clashrule](https://github.com/tomdegnan/clashrule), 节点数量: `214`
- [TG@getv2ray](https://t.me/getv2ray), 节点数量: `7`
- [changfengoss](https://github.com/ronghuaxueleng/get_v2), 节点数量: `902`
- [anaer/Sub](https://github.com/anaer/Sub), 节点数量: `193`
- [xrayfree/free-ssr-ss-v2ray-vpn-clash](https://github.com/xrayfree/free-ssr-ss-v2ray-vpn-clash), 节点数量: `99`
- [KYLELI1991/subscription_vless](https://github.com/KYLELI1991/subscription_vless), 节点数量: `1`
- [mhmhone/shadowrocket-free-subscribe](https://github.com/mhmhone/shadowrocket-free-subscribe), 节点数量: `36`
- [aiboboxx/v2rayfree](https://github.com/aiboboxx/v2rayfree), 节点数量: `55`
- [moneyfly1/sublist](https://github.com/moneyfly1/sublist), 节点数量: `32`
- [poduv/poduv](https://github.com/poduv/poduv), 节点数量: `14`
- [ok1991/v2ray](https://github.com/ok1991/v2ray), 节点数量: `1`
- [parkerpa/jsfxs](https://github.com/parkerpa/jsfxs), 节点数量: `1`
- [Pawdroid/Free-servers](https://github.com/Pawdroid/Free-servers), 节点数量: `1`
- [songkaik/Sub](https://github.com/songkaik/Sub), 节点数量: `1`
- [yosefwang/subscription](https://github.com/yosefwang/subscription), 节点数量: `29`
- [Nodefree.org](https://github.com/Fukki-Z/nodefree), 节点数量: `1`

## 客户端选择
### 主流桌面客户端
|                            MacOS                             |                            Linux                             |                           Windows                            | 简易描述                                           |
| :----------------------------------------------------------: | :----------------------------------------------------------: | :----------------------------------------------------------: | :------------------------------------------------- |
| [CFW](https://github.com/Fndroid/clash_for_windows_pkg/releases) | [CFW](https://github.com/Fndroid/clash_for_windows_pkg/releases) | [CFW(Clash For Windows)](https://github.com/Fndroid/clash_for_windows_pkg/releases) | SS, SSR, Trojan, Vmess, VLESS协议支持，策略分流能力强。            |
|     [Qv2ray](https://github.com/Qv2ray/Qv2ray/releases)      |     [Qv2ray](https://github.com/Qv2ray/Qv2ray/releases)      |     [Qv2ray](https://github.com/Qv2ray/Qv2ray/releases)      | SS, SSR, Trojan, Vmess, VLESS, Trojan-Go协议支持（需安装相关插件）。 |
|                              ×                               |                              ×                               |      [V2rayN](https://github.com/2dust/v2rayN/releases)      | SS, Trojan, Vmess, VLESS协议支持，有测速，测延迟功能，支持订阅，二维码，剪贴板导入及手动配置。                 |
|                              ×                               |                              ×                               |    [WinXray](https://github.com/TheMRLL/winxray/releases)    | SS, SSR, Trojan, Vmess, VLESS协议支持，支持自动连接最快节点。            |
|                              ×                               |                              ×                               | [Shadowsocks-windows](https://github.com/shadowsocks/shadowsocks-windows/releases) | SS协议支持， SS 专用客户端。                                       |
|                              ×                               |                              ×                               | [ShadowsocksR-windows](https://github.com/HMBSbige/ShadowsocksR-Windows/releases) | SSR协议支持，SSR 专用客户端。                                      |
|                [Surge](https://nssurge.com/)                 |                              ×                               |                              ×                               | SS, Trojan, Vmess协议支持，著名网络调试工具，策略分流能力强大，需付费。                        |
|   [ClashX](https://github.com/yichengchen/clashX/releases)   |                              ×                               |                              ×                               | SS, SSR, Trojan, Vmess协议支持，占用资源较少。                   |
|      [V2rayU](https://github.com/yanue/V2rayU/releases)      |                              ×                               |                              ×                               | SS, Trojan, Vmess协议支持，支持订阅，二维码，剪贴板导入，手动配置，二维码分享，与 V2RayN 类似。                        |

### 主流移动客户端
|                          iOS/iPadOS                          |                           Android                            | 简易描述                                                     |
| :----------------------------------------------------------: | :----------------------------------------------------------: | ------------------------------------------------------------ |
| [Shadowrocket](https://apps.apple.com/us/app/shadowrocket/id932747118) | [Shadowrocket](https://play.google.com/store/apps/details?id=com.v2cross.proxy) | SS, SSR, Trojan, Vmess, VLESS协议支持，iOS端需在非国区 App Store 购买，美区售价 $2.99；安卓端非与 iOS 端同一作者，不支持 SSR 协议，免费且内置免费节点。 |
|                [Surge](https://nssurge.com/)                 |                              ×                               | SS, Trojan, Vmess协议支持，iOS 端著名网络调试工具，需付费。                                  |
| [Quantumult X](https://apps.apple.com/us/app/quantumult-x/id1443988620) |                              ×                               | SS, SSR, Trojan, Vmess协议支持，需在非国区AppStore购买，美区售价$4.99。 |
| [Potatso Lite](https://apps.apple.com/us/app/potatso-lite/id1239860606) |                              ×                               | SS, SSR协议支持，需在非国区AppStore购买，免费。              |
|                              ×                               | [Surfboard](https://play.google.com/store/apps/details?id=com.getsurfboard) | SS, SSR, Vmess协议支持，安卓端网络调试软件，兼容 Surge 2 配置。 |
|                              ×                               | [CFA(Clash For Android)](https://github.com/Kr328/ClashForAndroid/releases) | SS, SSR, Trojan, Vmess协议支持。                             |
|                              ×                               |  [SagerNet](https://github.com/SagerNet/SagerNet/releases)   | SS, SSR, Trojan, Vmess, VLESS协议支持。                      |
|                              ×                               | [Shadowsocks-android](https://github.com/shadowsocks/shadowsocks-android/releases) | SS协议支持，安卓专用 SS 客户端。                                                 |
|                              ×                               | [ShadowsocksR-android](https://github.com/HMBSbige/ShadowsocksR-Android/releases) | SSR协议支持，安卓专用 SSR 客户端。                                                |
|                              ×                               |     [V2rayNG](https://github.com/2dust/v2rayNG/releases)     | SS, Trojan, Vmess, VLESS协议支持，v2ray 内核。                           |

## 机场推荐
免费节点失效太快，推荐一些性价比高的机场应急使用。
- [魔戒.net](https://www.mojie.cyou/#/register?code=sAbl0qtT)
  - 按量计费机场, 1¥10G, 10¥130G
  - 所有套餐均是一样的节点与一样的服务，所有套餐流量永不过期，用完为止，不限制客户端数量，最高可提供 2Gbps 峰值。
- [大迅云](https://daxun.club/#/register?code=JPmAFPav)
  - 最低月付 5¥50G, 购买 12¥ 及以上套餐免费领取奈飞 + 迪士尼 Plus 共享号
  - 原生IP负载均衡，流媒体解锁晚高峰油管秒开，主打性价比，有试用
- [阿伟云](https://awslcn.xyz/#/register?code=8C18uZwl)
  - 最低月付 1¥ 起, 9.99¥100G
  - 无带宽速率限制，有流媒体解锁，香港 BGP 中继线路

## 仓库声明
订阅节点仅作学习交流使用，只是对网络上节点的优选排序，用于查找资料，学习知识，不做任何违法行为。所有资源均来自互联网，仅供大家交流学习使用，出现违法问题概不负责。

## 星标统计
[![Stargazers over time](https://starchart.cc/alanbobs999/TopFreeProxies.svg)](https://starchart.cc/alanbobs999/TopFreeProxies)
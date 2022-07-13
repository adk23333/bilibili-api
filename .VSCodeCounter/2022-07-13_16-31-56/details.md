# Details

Date : 2022-07-13 16:31:56

Directory /Users/nemo/Desktop/Python/bilibili_api

Total : 156 files,  16198 codes, 3609 comments, 3678 blanks, all 23485 lines

[Summary](results.md) / Details / [Diff Summary](diff.md) / [Diff Details](diff-details.md)

## Files
| filename | language | code | comment | blank | total |
| :--- | :--- | ---: | ---: | ---: | ---: |
| [.github/CONTRIBUTING.md](/.github/CONTRIBUTING.md) | Markdown | 46 | 0 | 35 | 81 |
| [.github/ISSUE_TEMPLATE/config.yml](/.github/ISSUE_TEMPLATE/config.yml) | YAML | 1 | 0 | 0 | 1 |
| [.github/ISSUE_TEMPLATE/ivideo.md](/.github/ISSUE_TEMPLATE/ivideo.md) | Markdown | 8 | 0 | 3 | 11 |
| [.github/ISSUE_TEMPLATE/needs.md](/.github/ISSUE_TEMPLATE/needs.md) | Markdown | 8 | 0 | 3 | 11 |
| [.github/ISSUE_TEMPLATE/question.md](/.github/ISSUE_TEMPLATE/question.md) | Markdown | 12 | 0 | 7 | 19 |
| [.github/ISSUE_TEMPLATE/suggestion.md](/.github/ISSUE_TEMPLATE/suggestion.md) | Markdown | 8 | 0 | 2 | 10 |
| [.github/ISSUE_TEMPLATE/troubleshooting.md](/.github/ISSUE_TEMPLATE/troubleshooting.md) | Markdown | 22 | 0 | 13 | 35 |
| [.github/PULL_REQUEST_TEMPLATE.md](/.github/PULL_REQUEST_TEMPLATE.md) | Markdown | 4 | 2 | 3 | 9 |
| [.github/workflows/python-publish.yml](/.github/workflows/python-publish.yml) | YAML | 24 | 2 | 6 | 32 |
| [README.md](/README.md) | Markdown | 125 | 0 | 56 | 181 |
| [bilibili_api/__init__.py](/bilibili_api/__init__.py) | Python | 47 | 2 | 7 | 56 |
| [bilibili_api/app.py](/bilibili_api/app.py) | Python | 66 | 31 | 13 | 110 |
| [bilibili_api/article.py](/bilibili_api/article.py) | Python | 489 | 102 | 199 | 790 |
| [bilibili_api/ass.py](/bilibili_api/ass.py) | Python | 129 | 80 | 14 | 223 |
| [bilibili_api/audio.py](/bilibili_api/audio.py) | Python | 48 | 51 | 24 | 123 |
| [bilibili_api/bangumi.py](/bilibili_api/bangumi.py) | Python | 124 | 83 | 43 | 250 |
| [bilibili_api/channel.py](/bilibili_api/channel.py) | Python | 67 | 48 | 18 | 133 |
| [bilibili_api/cheese.py](/bilibili_api/cheese.py) | Python | 392 | 106 | 55 | 553 |
| [bilibili_api/comment.py](/bilibili_api/comment.py) | Python | 115 | 127 | 36 | 278 |
| [bilibili_api/data/api/README.md](/bilibili_api/data/api/README.md) | Markdown | 3 | 0 | 3 | 6 |
| [bilibili_api/data/api/app.json](/bilibili_api/data/api/app.json) | JSON | 29 | 0 | 0 | 29 |
| [bilibili_api/data/api/article.json](/bilibili_api/data/api/article.json) | JSON | 64 | 0 | 0 | 64 |
| [bilibili_api/data/api/audio.json](/bilibili_api/data/api/audio.json) | JSON | 108 | 0 | 0 | 108 |
| [bilibili_api/data/api/bangumi.json](/bilibili_api/data/api/bangumi.json) | JSON | 106 | 0 | 0 | 106 |
| [bilibili_api/data/api/channel.json](/bilibili_api/data/api/channel.json) | JSON | 14 | 0 | 0 | 14 |
| [bilibili_api/data/api/cheese.json](/bilibili_api/data/api/cheese.json) | JSON | 37 | 0 | 0 | 37 |
| [bilibili_api/data/api/common.json](/bilibili_api/data/api/common.json) | JSON | 186 | 0 | 0 | 186 |
| [bilibili_api/data/api/dynamic.json](/bilibili_api/data/api/dynamic.json) | JSON | 189 | 0 | 0 | 189 |
| [bilibili_api/data/api/favorite-list.json](/bilibili_api/data/api/favorite-list.json) | JSON | 160 | 0 | 0 | 160 |
| [bilibili_api/data/api/homepage.json](/bilibili_api/data/api/homepage.json) | JSON | 35 | 0 | 1 | 36 |
| [bilibili_api/data/api/interactive_video.json](/bilibili_api/data/api/interactive_video.json) | JSON | 36 | 0 | 1 | 37 |
| [bilibili_api/data/api/live.json](/bilibili_api/data/api/live.json) | JSON | 362 | 0 | 1 | 363 |
| [bilibili_api/data/api/login.json](/bilibili_api/data/api/login.json) | JSON | 81 | 0 | 0 | 81 |
| [bilibili_api/data/api/rank.json](/bilibili_api/data/api/rank.json) | JSON | 40 | 0 | 1 | 41 |
| [bilibili_api/data/api/search.json](/bilibili_api/data/api/search.json) | JSON | 25 | 0 | 0 | 25 |
| [bilibili_api/data/api/toview.json](/bilibili_api/data/api/toview.json) | JSON | 41 | 0 | 0 | 41 |
| [bilibili_api/data/api/user.json](/bilibili_api/data/api/user.json) | JSON | 316 | 0 | 0 | 316 |
| [bilibili_api/data/api/video.json](/bilibili_api/data/api/video.json) | JSON | 342 | 0 | 1 | 343 |
| [bilibili_api/data/api/video_uploader.json](/bilibili_api/data/api/video_uploader.json) | JSON | 73 | 0 | 3 | 76 |
| [bilibili_api/data/channel.json](/bilibili_api/data/channel.json) | JSON | 1,716 | 0 | 0 | 1,716 |
| [bilibili_api/data/countries_codes.json](/bilibili_api/data/countries_codes.json) | JSON | 1,077 | 0 | 0 | 1,077 |
| [bilibili_api/dynamic.py](/bilibili_api/dynamic.py) | Python | 212 | 130 | 55 | 397 |
| [bilibili_api/exceptions/ApiException.py](/bilibili_api/exceptions/ApiException.py) | Python | 6 | 8 | 5 | 19 |
| [bilibili_api/exceptions/ArgsException.py](/bilibili_api/exceptions/ArgsException.py) | Python | 5 | 12 | 5 | 22 |
| [bilibili_api/exceptions/CredentialNoBiliJctException.py](/bilibili_api/exceptions/CredentialNoBiliJctException.py) | Python | 5 | 8 | 5 | 18 |
| [bilibili_api/exceptions/CredentialNoBuvid3Exception.py](/bilibili_api/exceptions/CredentialNoBuvid3Exception.py) | Python | 5 | 8 | 5 | 18 |
| [bilibili_api/exceptions/CredentialNoDedeUserIDException.py](/bilibili_api/exceptions/CredentialNoDedeUserIDException.py) | Python | 5 | 8 | 4 | 17 |
| [bilibili_api/exceptions/CredentialNoSessdataException.py](/bilibili_api/exceptions/CredentialNoSessdataException.py) | Python | 5 | 8 | 5 | 18 |
| [bilibili_api/exceptions/DanmakuClosedException.py](/bilibili_api/exceptions/DanmakuClosedException.py) | Python | 5 | 8 | 5 | 18 |
| [bilibili_api/exceptions/DynamicExceedImagesException.py](/bilibili_api/exceptions/DynamicExceedImagesException.py) | Python | 5 | 8 | 5 | 18 |
| [bilibili_api/exceptions/LiveException.py](/bilibili_api/exceptions/LiveException.py) | Python | 5 | 4 | 4 | 13 |
| [bilibili_api/exceptions/LoginError.py](/bilibili_api/exceptions/LoginError.py) | Python | 5 | 12 | 5 | 22 |
| [bilibili_api/exceptions/NetworkException.py](/bilibili_api/exceptions/NetworkException.py) | Python | 8 | 14 | 6 | 28 |
| [bilibili_api/exceptions/ResponseCodeException.py](/bilibili_api/exceptions/ResponseCodeException.py) | Python | 9 | 15 | 6 | 30 |
| [bilibili_api/exceptions/ResponseException.py](/bilibili_api/exceptions/ResponseException.py) | Python | 5 | 13 | 5 | 23 |
| [bilibili_api/exceptions/VideoUploadException.py](/bilibili_api/exceptions/VideoUploadException.py) | Python | 5 | 12 | 5 | 22 |
| [bilibili_api/exceptions/__init__.py](/bilibili_api/exceptions/__init__.py) | Python | 12 | 0 | 1 | 13 |
| [bilibili_api/favorite_list.py](/bilibili_api/favorite_list.py) | Python | 177 | 167 | 77 | 421 |
| [bilibili_api/homepage.py](/bilibili_api/homepage.py) | Python | 19 | 35 | 11 | 65 |
| [bilibili_api/html/captcha.html](/bilibili_api/html/captcha.html) | HTML | 498 | 0 | 65 | 563 |
| [bilibili_api/html/done.html](/bilibili_api/html/done.html) | HTML | 13 | 0 | 1 | 14 |
| [bilibili_api/interactive_video.py](/bilibili_api/interactive_video.py) | Python | 43 | 44 | 16 | 103 |
| [bilibili_api/live.py](/bilibili_api/live.py) | Python | 693 | 322 | 139 | 1,154 |
| [bilibili_api/login.py](/bilibili_api/login.py) | Python | 336 | 139 | 55 | 530 |
| [bilibili_api/rank.py](/bilibili_api/rank.py) | Python | 21 | 41 | 13 | 75 |
| [bilibili_api/search.py](/bilibili_api/search.py) | Python | 22 | 37 | 9 | 68 |
| [bilibili_api/settings.py](/bilibili_api/settings.py) | Python | 4 | 8 | 2 | 14 |
| [bilibili_api/user.py](/bilibili_api/user.py) | Python | 364 | 381 | 101 | 846 |
| [bilibili_api/utils/AsyncEvent.py](/bilibili_api/utils/AsyncEvent.py) | Python | 29 | 40 | 12 | 81 |
| [bilibili_api/utils/BytesReader.py](/bilibili_api/utils/BytesReader.py) | Python | 85 | 136 | 23 | 244 |
| [bilibili_api/utils/Credential.py](/bilibili_api/utils/Credential.py) | Python | 34 | 59 | 14 | 107 |
| [bilibili_api/utils/Danmaku.py](/bilibili_api/utils/Danmaku.py) | Python | 62 | 39 | 17 | 118 |
| [bilibili_api/utils/__init__.py](/bilibili_api/utils/__init__.py) | Python | 0 | 0 | 1 | 1 |
| [bilibili_api/utils/aid_bvid_transformer.py](/bilibili_api/utils/aid_bvid_transformer.py) | Python | 29 | 23 | 9 | 61 |
| [bilibili_api/utils/captcha.py](/bilibili_api/utils/captcha.py) | Python | 153 | 84 | 23 | 260 |
| [bilibili_api/utils/json2srt.py](/bilibili_api/utils/json2srt.py) | Python | 46 | 9 | 4 | 59 |
| [bilibili_api/utils/network.py](/bilibili_api/utils/network.py) | Python | 112 | 50 | 42 | 204 |
| [bilibili_api/utils/network_httpx.py](/bilibili_api/utils/network_httpx.py) | Python | 113 | 50 | 42 | 205 |
| [bilibili_api/utils/parse_link.py](/bilibili_api/utils/parse_link.py) | Python | 147 | 63 | 27 | 237 |
| [bilibili_api/utils/short.py](/bilibili_api/utils/short.py) | Python | 21 | 14 | 3 | 38 |
| [bilibili_api/utils/srt2ass.py](/bilibili_api/utils/srt2ass.py) | Python | 99 | 31 | 24 | 154 |
| [bilibili_api/utils/sync.py](/bilibili_api/utils/sync.py) | Python | 15 | 9 | 6 | 30 |
| [bilibili_api/utils/utils.py](/bilibili_api/utils/utils.py) | Python | 102 | 38 | 27 | 167 |
| [bilibili_api/utils/varint.py](/bilibili_api/utils/varint.py) | Python | 14 | 14 | 3 | 31 |
| [bilibili_api/video.py](/bilibili_api/video.py) | Python | 860 | 494 | 171 | 1,525 |
| [bilibili_api/video_uploader.py](/bilibili_api/video_uploader.py) | Python | 371 | 278 | 109 | 758 |
| [bilibili_api/vote.py](/bilibili_api/vote.py) | Python | 7 | 15 | 5 | 27 |
| [changelogs/v1.md](/changelogs/v1.md) | Markdown | 55 | 0 | 16 | 71 |
| [changelogs/v10.md](/changelogs/v10.md) | Markdown | 72 | 0 | 33 | 105 |
| [changelogs/v2.md](/changelogs/v2.md) | Markdown | 37 | 0 | 10 | 47 |
| [changelogs/v3.md](/changelogs/v3.md) | Markdown | 53 | 0 | 11 | 64 |
| [changelogs/v4.md](/changelogs/v4.md) | Markdown | 16 | 0 | 5 | 21 |
| [changelogs/v5.md](/changelogs/v5.md) | Markdown | 19 | 0 | 6 | 25 |
| [changelogs/v6.md](/changelogs/v6.md) | Markdown | 32 | 0 | 5 | 37 |
| [changelogs/v7.md](/changelogs/v7.md) | Markdown | 6 | 0 | 1 | 7 |
| [changelogs/v8.md](/changelogs/v8.md) | Markdown | 19 | 0 | 4 | 23 |
| [changelogs/v9.md](/changelogs/v9.md) | Markdown | 28 | 0 | 19 | 47 |
| [docs/README.md](/docs/README.md) | Markdown | 125 | 0 | 56 | 181 |
| [docs/_sidebar.md](/docs/_sidebar.md) | Markdown | 43 | 0 | 1 | 44 |
| [docs/b23tv.md](/docs/b23tv.md) | Markdown | 6 | 0 | 3 | 9 |
| [docs/configuration.md](/docs/configuration.md) | Markdown | 13 | 0 | 7 | 20 |
| [docs/examples/article.md](/docs/examples/article.md) | Markdown | 10 | 0 | 9 | 19 |
| [docs/examples/ass.md](/docs/examples/ass.md) | Markdown | 5 | 0 | 2 | 7 |
| [docs/examples/audio.md](/docs/examples/audio.md) | Markdown | 39 | 0 | 14 | 53 |
| [docs/examples/bangumi.md](/docs/examples/bangumi.md) | Markdown | 28 | 0 | 13 | 41 |
| [docs/examples/comment.md](/docs/examples/comment.md) | Markdown | 29 | 0 | 10 | 39 |
| [docs/examples/dynamic.md](/docs/examples/dynamic.md) | Markdown | 44 | 0 | 14 | 58 |
| [docs/examples/favorite_list.md](/docs/examples/favorite_list.md) | Markdown | 11 | 0 | 6 | 17 |
| [docs/examples/interactive_video.md](/docs/examples/interactive_video.md) | Markdown | 164 | 0 | 51 | 215 |
| [docs/examples/live.md](/docs/examples/live.md) | Markdown | 63 | 0 | 19 | 82 |
| [docs/examples/user.md](/docs/examples/user.md) | Markdown | 63 | 0 | 26 | 89 |
| [docs/examples/video.md](/docs/examples/video.md) | Markdown | 110 | 0 | 30 | 140 |
| [docs/examples/video_uploader.md](/docs/examples/video_uploader.md) | Markdown | 33 | 0 | 9 | 42 |
| [docs/get-credential.md](/docs/get-credential.md) | Markdown | 29 | 0 | 26 | 55 |
| [docs/history.html](/docs/history.html) | HTML | 57 | 0 | 11 | 68 |
| [docs/history.md](/docs/history.md) | Markdown | 3 | 0 | 2 | 5 |
| [docs/index.html](/docs/index.html) | HTML | 68 | 1 | 6 | 75 |
| [docs/login.md](/docs/login.md) | Markdown | 84 | 0 | 21 | 105 |
| [docs/modules/app.md](/docs/modules/app.md) | Markdown | 29 | 0 | 14 | 43 |
| [docs/modules/article.md](/docs/modules/article.md) | Markdown | 52 | 0 | 41 | 93 |
| [docs/modules/ass.md](/docs/modules/ass.md) | Markdown | 51 | 0 | 14 | 65 |
| [docs/modules/audio.md](/docs/modules/audio.md) | Markdown | 60 | 0 | 44 | 104 |
| [docs/modules/bangumi.md](/docs/modules/bangumi.md) | Markdown | 95 | 0 | 71 | 166 |
| [docs/modules/bilibili_api.md](/docs/modules/bilibili_api.md) | Markdown | 146 | 0 | 94 | 240 |
| [docs/modules/channel.md](/docs/modules/channel.md) | Markdown | 28 | 0 | 19 | 47 |
| [docs/modules/cheese.md](/docs/modules/cheese.md) | Markdown | 87 | 0 | 63 | 150 |
| [docs/modules/comment.md](/docs/modules/comment.md) | Markdown | 91 | 0 | 52 | 143 |
| [docs/modules/dynamic.md](/docs/modules/dynamic.md) | Markdown | 79 | 0 | 53 | 132 |
| [docs/modules/favorite_list.md](/docs/modules/favorite_list.md) | Markdown | 150 | 0 | 80 | 230 |
| [docs/modules/homepage.md](/docs/modules/homepage.md) | Markdown | 30 | 0 | 20 | 50 |
| [docs/modules/interactive_video.md](/docs/modules/interactive_video.md) | Markdown | 37 | 0 | 20 | 57 |
| [docs/modules/live.md](/docs/modules/live.md) | Markdown | 261 | 0 | 156 | 417 |
| [docs/modules/login.md](/docs/modules/login.md) | Markdown | 102 | 0 | 62 | 164 |
| [docs/modules/rank.md](/docs/modules/rank.md) | Markdown | 22 | 0 | 18 | 40 |
| [docs/modules/search.md](/docs/modules/search.md) | Markdown | 30 | 0 | 14 | 44 |
| [docs/modules/user.md](/docs/modules/user.md) | Markdown | 276 | 0 | 180 | 456 |
| [docs/modules/video.md](/docs/modules/video.md) | Markdown | 283 | 0 | 166 | 449 |
| [docs/modules/video_uploader.md](/docs/modules/video_uploader.md) | Markdown | 96 | 0 | 51 | 147 |
| [docs/modules/vote.md](/docs/modules/vote.md) | Markdown | 10 | 0 | 6 | 16 |
| [docs/package.json](/docs/package.json) | JSON | 29 | 0 | 1 | 30 |
| [docs/parse_link.md](/docs/parse_link.md) | Markdown | 60 | 0 | 24 | 84 |
| [docs/search.js](/docs/search.js) | JavaScript | 1 | 0 | 0 | 1 |
| [docs/sync-executor.md](/docs/sync-executor.md) | Markdown | 34 | 0 | 16 | 50 |
| [docs/theme.css](/docs/theme.css) | CSS | 861 | 0 | 178 | 1,039 |
| [docs/vote_id.md](/docs/vote_id.md) | Markdown | 46 | 0 | 12 | 58 |
| [install.py](/install.py) | Python | 11 | 1 | 7 | 19 |
| [js/models/Credential.ts](/js/models/Credential.ts) | TypeScript | 19 | 0 | 4 | 23 |
| [js/models/Proxy.ts](/js/models/Proxy.ts) | TypeScript | 12 | 0 | 2 | 14 |
| [js/package.json](/js/package.json) | JSON | 33 | 0 | 1 | 34 |
| [js/tests/main.ts](/js/tests/main.ts) | TypeScript | 19 | 0 | 5 | 24 |
| [js/tests/tsconfig.json](/js/tests/tsconfig.json) | JSON with Comments | 7 | 0 | 0 | 7 |
| [js/tsconfig.json](/js/tsconfig.json) | JSON with Comments | 12 | 83 | 8 | 103 |
| [js/utils/network.ts](/js/utils/network.ts) | TypeScript | 55 | 0 | 4 | 59 |
| [requirements.txt](/requirements.txt) | pip requirements | 14 | 1 | 1 | 16 |
| [scripts/lint.py](/scripts/lint.py) | Python | 2 | 1 | 2 | 5 |
| [setup.py](/setup.py) | Python | 38 | 0 | 4 | 42 |

[Summary](results.md) / Details / [Diff Summary](diff.md) / [Diff Details](diff-details.md)
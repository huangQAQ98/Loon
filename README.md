# Loon 配置仓库

个人 Loon 代理配置，包含主配置、插件、脚本和规则集。

## 目录结构

```
Loon/
├── profile/          # 主配置文件
├── plugins/          # 插件模块
├── scripts/          # JavaScript 脚本
└── rules/            # 规则集
```

## 快速开始

### 1. 导入主配置

Loon → 配置 → 所有配置文件 → 点击右上角 `+` → 从链接导入：

```
https://raw.githubusercontent.com/curtinp118/Loon/main/profile/Loon.conf
```

### 2. 添加插件

Loon → 配置 → 所有配置文件 → 点击右上角 `+` → 从链接导入：

```
https://raw.githubusercontent.com/curtinp118/Loon/main/plugins/glados.plugin
```

### 3. 配置节点

**方式一：编辑配置文件**

修改 `profile/Loon.conf` 中的 `[Proxy]` 和 `[Remote Proxy]` 部分，填入订阅链接。

**方式二：UI 配置**

Loon → 配置 → 所有节点 → 点击右上角 `+` → 从链接导入订阅。

### 4. MITM 证书

签到和解锁功能需要 MITM，请在 Loon 中安装并信任 CA 证书。

## 配置说明

- **DNS 优化**：加密 DNS + 域名分流
- **策略组**：手动选择 + 自动测速
- **远程规则**：17 条分类订阅
- **广告拦截**：自动过滤广告请求
- **插件扩展**：签到 / 解锁 / 增强功能

## 鸣谢
### 特别致谢
<div style="overflow-x: auto;">
    <table width="100%" height="100%" style="white-space: nowrap;">
        <tr>
            <td colspan="4" align="center">
                <b>作者（按 GitHub 用户名字母顺序排序）</b>
            </td>
        </tr>
        <tr>
            <td width="200px"><a href="https://github.com/001ProMax"><em>@001ProMax</em></a></td>
            <td width="200px"><a href="https://github.com/217heidai"><em>@217heidai</em></a></td>
            <td width="200px"><a href="https://github.com/anker1209"><em>@anker1209</em></a></td>
            <td width="200px"><a href="https://github.com/anyehttp"><em>@anyehttp</em></a></td>
        </tr>
        <tr>
            <td width="200px"><a href="https://github.com/app2smile"><em>@app2smile</em></a></td>
            <td width="200px"><a href="https://github.com/blackmatrix7"><em>@blackmatrix7</em></a></td>
            <td width="200px"><a href="https://github.com/chavyleung"><em>@chavyleung</em></a></td>
            <td width="200px"><a href="https://github.com/ChinaTelecomOperators"><em>@ChinaTelecomOperators</em></a></td>
        </tr>
        <tr>
            <td width="200px"><a href="https://github.com/Choler"><em>@Choler</em></a></td>
            <td width="200px"><a href="https://github.com/chxm1023"><em>@chxm1023</em></a></td>
            <td width="200px"><a href="https://github.com/CKYB"><em>@CKYB</em></a></td>
            <td width="200px"><a href="https://github.com/ClydeTime"><em>@ClydeTime</em></a></td>
        </tr>
        <tr>
            <td width="200px"><a href="https://github.com/curtinp118"><em>@curtinp118</em></a></td>
            <td width="200px"><a href="https://github.com/dcpengx"><em>@dcpengx</em></a></td>
            <td width="200px"><a href="https://github.com/ddgksf2013"><em>@ddgksf2013</em></a></td>
            <td width="200px"><a href="https://github.com/fangkuia"><em>@fangkuia</em></a></td>
        </tr>
        <tr>
            <td width="200px"><a href="https://github.com/fmz200"><em>@fmz200</em></a></td>
            <td width="200px"><a href="https://github.com/FoKit"><em>@FoKit</em></a></td>
            <td width="200px"><a href="https://github.com/githubdulong"><em>@githubdulong</em></a></td>
            <td width="200px"><a href="https://github.com/GoodHolidays"><em>@GoodHolidays</em></a></td>
        </tr>
        <tr>
            <td width="200px"><a href="https://github.com/Guding88"><em>@Guding88</em></a></td>
            <td width="200px"><a href="https://github.com/hfg-gmuend"><em>@hfg-gmuend</em></a></td>
            <td width="200px"><a href="https://github.com/huskydsb"><em>@huskydsb</em></a></td>
            <td width="200px"><a href="https://github.com/I-am-R-E"><em>@I-am-R-E</em></a></td>
        </tr>
        <tr>
            <td width="200px"><a href="https://github.com/iniwex5"><em>@iniwex5</em></a></td>
            <td width="200px"><a href="https://github.com/kelv1n1n"><em>@kelv1n1n</em></a></td>
            <td width="200px"><a href="https://github.com/Keywos"><em>@Keywos</em></a></td>
            <td width="200px"><a href="https://github.com/kokoryh"><em>@kokoryh</em></a></td>
        </tr>
        <tr>
            <td width="200px"><a href="https://github.com/KOP-XIAO"><em>@KOP-XIAO</em></a></td>
            <td width="200px"><a href="https://github.com/limbopro"><em>@limbopro</em></a></td>
            <td width="200px"><a href="https://github.com/luestr"><em>@luestr</em></a></td>
            <td width="200px"><a href="https://github.com/Maasea"><em>@Maasea</em></a></td>
        </tr>
        <tr>
            <td width="200px"><a href="https://github.com/Marol62926"><em>@Marol62926</em></a></td>
            <td width="200px"><a href="https://github.com/meichiny"><em>@meichiny</em></a></td>
            <td width="200px"><a href="https://github.com/mieqq"><em>@mieqq</em></a></td>
            <td width="200px"><a href="https://github.com/mist-whisper"><em>@mist-whisper</em></a></td>
        </tr>
        <tr>
            <td width="200px"><a href="https://github.com/mw418"><em>@mw418</em></a></td>
            <td width="200px"><a href="https://github.com/neishe321"><em>@neishe321</em></a></td>
            <td width="200px"><a href="https://github.com/NobyDa"><em>@NobyDa</em></a></td>
            <td width="200px"><a href="https://github.com/Peng-YM"><em>@Peng-YM</em></a></td>
        </tr>
        <tr>
            <td width="200px"><a href="https://github.com/Repcz"><em>@Repcz</em></a></td>
            <td width="200px"><a href="https://github.com/RuCu6"><em>@RuCu6</em></a></td>
            <td width="200px"><a href="https://github.com/Sliverkiss"><em>@Sliverkiss</em></a></td>
            <td width="200px"><a href="https://github.com/suiyuran"><em>@suiyuran</em></a></td>
        </tr>
        <tr>
            <td width="200px"><a href="https://github.com/VirgilClyne"><em>@VirgilClyne</em></a></td>
            <td width="200px"><a href="https://github.com/wf021325"><em>@wf021325</em></a></td>
            <td width="200px"><a href="https://github.com/xream"><em>@xream</em></a></td>
            <td width="200px"><a href="https://github.com/Yswag"><em>@Yswag</em></a></td>
        </tr>
        <tr>
            <td width="200px"><a href="https://github.com/Yu9191"><em>@Yu9191</em></a></td>
            <td width="200px"><a href="https://github.com/Yuheng0101"><em>@Yuheng0101</em></a></td>
            <td width="200px"><a href="https://github.com/ZenmoFeiShi"><em>@ZenmoFeiShi</em></a></td>
            <td width="200px"><a href="https://github.com/zirawell"><em>@zirawell</em></a></td>
        </tr>
        <tr>
            <td width="200px"><a href="https://github.com/zmqcherish"><em>@zmqcherish</em></a></td>
            <td width="200px"><a href="https://github.com/zZPiglet"><em>@zZPiglet</em></a></td>
            <td width="200px"></td>
            <td width="200px"></td>
        </tr>
    </table>
</div>
### 第三方规则仓库

- [blackmatrix7/ios_rule_script](https://github.com/blackmatrix7/ios_rule_script) - 提供主要分流规则
- [Loyalsoldier/geoip](https://github.com/Loyalsoldier/geoip) - GeoIP 数据库
- [Masaiki/GeoIP2-CN](https://gitlab.com/Masaiki/GeoIP2-CN) - 中国 GeoIP 数据库

### 分流图标

- [Koolson/Qure](https://github.com/Koolson/Qure) - 策略组图标
- [Orz-3/mini](https://github.com/Orz-3/mini) - 分流图标
- [fmz200/wool_scripts](https://github.com/fmz200/wool_scripts) - 图标资源

## License

[MIT](LICENSE)

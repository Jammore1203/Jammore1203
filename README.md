<div align="center">

<img src="assets/header.svg" width="100%" alt="joe@arch ~ whoami"/>

<a href="https://josephcreasy.co.uk"><img src="https://img.shields.io/badge/josephcreasy.co.uk-1d2021?style=for-the-badge&logo=gnometerminal&logoColor=fabd2f" alt="website"/></a>
<a href="https://redfoxss.co.uk"><img src="https://img.shields.io/badge/RedFox-1d2021?style=for-the-badge&logo=firefoxbrowser&logoColor=fb4934" alt="RedFox"/></a>
<a href="https://cratess.com"><img src="https://img.shields.io/badge/play_Cratess-1d2021?style=for-the-badge&logo=itchdotio&logoColor=fe8019" alt="Cratess"/></a>
<img src="https://img.shields.io/badge/btw_I_use-Arch-1d2021?style=for-the-badge&logo=archlinux&logoColor=83a598&labelColor=1d2021" alt="arch"/>

<br/><br/>

<img src="assets/numbers.svg" width="100%" alt="50k+ lines shipped · 28k lines of Rust in one game · 138,639 neurons simulated · 30+ sites on one CMS · 0 asset files"/>

</div>

<br/>

> I build the whole thing: the product, the server it runs on, and the business around it.
> Founder of **RedFox**, maker of **Cratess**, and I write engines, simulators and AI agents for fun.

## ▸ in production

<table>
<tr>
<td width="50%" valign="top">

<a href="https://redfoxss.co.uk"><img src="assets/redfox.jpg" alt="RedFox website"/></a>

### 🦊 [RedFox](https://redfoxss.co.uk)
**My web agency, running on a CMS I wrote.** A multi-tenant, Shopify-style platform:
one PHP codebase serves every client site with its own theme, blocks, admin, shop,
bookings and contact forms, plus per-tenant CSP, rate limiting and CSRF.
**30+ sites** built on it. I run the hosting and mail myself.

`PHP` `MariaDB` `Docker` `Apache` `self-hosted mail`

</td>
<td width="50%" valign="top">

<a href="https://cratess.com"><img src="assets/cratess-market.jpg" alt="Cratess market"/></a>

### 🦆 [Cratess](https://cratess.com)
**A free browser stock-market game, with rubber ducks.** A real **order-book market**
(bids, asks, spreads) with NPC market makers, crates across **7 rarity tiers**, fusion,
auctions, clans, gifting, friends/chat, daily streaks, arcade mini-games and Stripe
payments. Live now, [go play it](https://cratess.com).

`PHP MVC` `MariaDB` `Stripe` `cron-driven NPC traders`

</td>
</tr>
</table>

## ▸ built for fun (the hard way)

<table>
<tr>
<td width="33%" valign="top">

### 🔫 [hardpoint](https://github.com/Jammore1203/hardpoint)
A 2002-console-style multiplayer arena FPS in **28k lines of Rust**. 12 maps, 5 modes,
25 weapons, bots that play the objective, authoritative UDP netcode.
**Every texture, mesh, sound and music track is generated in code.** No asset folder.

</td>
<td width="33%" valign="top">

### 🪰 [flybrain-trader](https://github.com/Jammore1203/flybrain-trader)
A **complete fruit-fly brain** (FlyWire: 138,639 neurons, 15M synapses) simulated
on the GPU, rewarded with dopamine for good trades. A population **evolves** on a year
of BTC history, and the champion trades live.

</td>
<td width="33%" valign="top">

### 🤖 [jarvis](https://github.com/Jammore1203/jarvis)
My personal AI agent on the **Claude Agent SDK**. Lives in Telegram, talks back with
local TTS, reads mail/calendar/location, and keeps an Obsidian vault as memory.
It also **rewrites its own self-model**.

</td>
</tr>
<tr>
<td width="33%" valign="top">

### 🔁 [git-autosync](https://github.com/Jammore1203/git-autosync)
Hourly commit+push on a systemd timer, which **refuses to leak**: secret scanning,
per-repo denylists, size caps, desktop alerts.

</td>
<td width="33%" valign="top">

### 🎨 [dotfiles](https://github.com/Jammore1203/dotfiles)
Gruvbox everything on Arch + Plasma. kitty, starship, a hand-tuned EQ for my
headphones, and K95 G-key macros.

</td>
<td width="33%" valign="top">

### 👾 [pacman](https://github.com/Jammore1203/pacman)
Pac-Man, but with guns. Generated maps, a hotbar and a leaderboard, in vanilla JS.

</td>
</tr>
</table>

## ▸ `cat joe.rs`

```rust
pub struct Joe {
    based_in:   &'static str,
    runs:       [&'static str; 2],
    daily:      Vec<&'static str>,
    currently:  &'static str,
    philosophy: &'static str,
}

impl Default for Joe {
    fn default() -> Self {
        Joe {
            based_in:   "UK 🇬🇧",
            runs:       ["RedFox Software Solutions", "Cratess"],
            daily:      vec!["Rust", "Python", "PHP", "C#", "JS", "Bash", "SQL"],
            currently:  "getting RedFox clients + teaching an agent to be useful",
            philosophy: "if it doesn't run in production, it doesn't count",
        }
    }
}
```

## ▸ stack

<div align="center">

![Rust](https://img.shields.io/badge/Rust-1d2021?style=flat-square&logo=rust&logoColor=fe8019)
![Python](https://img.shields.io/badge/Python-1d2021?style=flat-square&logo=python&logoColor=fabd2f)
![PHP](https://img.shields.io/badge/PHP-1d2021?style=flat-square&logo=php&logoColor=83a598)
![Laravel](https://img.shields.io/badge/Laravel-1d2021?style=flat-square&logo=laravel&logoColor=fb4934)
![C#](https://img.shields.io/badge/C%23-1d2021?style=flat-square&logo=dotnet&logoColor=d3869b)
![JavaScript](https://img.shields.io/badge/JavaScript-1d2021?style=flat-square&logo=javascript&logoColor=fabd2f)
![PyTorch](https://img.shields.io/badge/PyTorch-1d2021?style=flat-square&logo=pytorch&logoColor=fb4934)
![Claude](https://img.shields.io/badge/Claude_Agent_SDK-1d2021?style=flat-square&logo=anthropic&logoColor=fe8019)
<br/>
![MariaDB](https://img.shields.io/badge/MariaDB-1d2021?style=flat-square&logo=mariadb&logoColor=ebdbb2)
![MySQL](https://img.shields.io/badge/MySQL-1d2021?style=flat-square&logo=mysql&logoColor=83a598)
![Docker](https://img.shields.io/badge/Docker-1d2021?style=flat-square&logo=docker&logoColor=83a598)
![Apache](https://img.shields.io/badge/Apache-1d2021?style=flat-square&logo=apache&logoColor=fb4934)
![Stripe](https://img.shields.io/badge/Stripe-1d2021?style=flat-square&logo=stripe&logoColor=d3869b)
![Arch](https://img.shields.io/badge/Arch-1d2021?style=flat-square&logo=archlinux&logoColor=83a598)
![Neovim](https://img.shields.io/badge/Neovim-1d2021?style=flat-square&logo=neovim&logoColor=b8bb26)
![Figma](https://img.shields.io/badge/Figma-1d2021?style=flat-square&logo=figma&logoColor=d3869b)
![Blender](https://img.shields.io/badge/Blender-1d2021?style=flat-square&logo=blender&logoColor=fe8019)
![Arduino](https://img.shields.io/badge/Arduino-1d2021?style=flat-square&logo=arduino&logoColor=8ec07c)

</div>

## ▸ numbers

<div align="center">
<img height="165" src="https://github-readme-stats.vercel.app/api?username=Jammore1203&show_icons=true&theme=gruvbox&hide_border=true&include_all_commits=true&count_private=true&bg_color=1d2021" />
<img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Jammore1203&layout=compact&theme=gruvbox&hide_border=true&langs_count=8&bg_color=1d2021" />
<br/>
<img width="100%" src="https://github-readme-activity-graph.vercel.app/graph?username=Jammore1203&bg_color=1d2021&color=ebdbb2&line=fe8019&point=fabd2f&area=true&area_color=fe8019&hide_border=true&radius=12" />
<br/>
<img src="https://streak-stats.demolab.com?user=Jammore1203&theme=gruvbox&hide_border=true&background=1d2021" />
</div>

## ▸ lately

<!--START_SECTION:activity-->
<!--END_SECTION:activity-->

<div align="center">

<img width="100%" src="https://raw.githubusercontent.com/Jammore1203/Jammore1203/output/snake.svg" alt="snake eating my contributions"/>

<img src="https://komarev.com/ghpvc/?username=jammore1203&label=views&color=1d2021&style=flat-square" alt="views"/>

<sub><code>:wq</code></sub>

</div>

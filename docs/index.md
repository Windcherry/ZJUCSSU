---
hide:
  - navigation
  - toc
---

<link rel="stylesheet" href="assets/cards/css/cards/base.css" />
<link rel="stylesheet" href="assets/cards/css/cards.css" />
<link rel="stylesheet" href="assets/cards/assets/index.c9fa2768.css" />

<style>
.homepage-wrapper {
    display: grid;
    grid-template-columns: 1fr;
    gap: 2rem;
    align-items: center;
    position: relative;
    max-width: 1000px;
    margin: 0 auto;
    padding-top: 4rem;
}
@media screen and (min-width: 900px) {
    .homepage-wrapper {
        grid-template-columns: 1fr 400px;
    }
}
.intro-section h1 {
    font-size: 2.5rem;
    margin-bottom: 1rem;
    font-weight: bold;
    border: none;
}
.intro-section p {
    font-size: 1.1rem;
    margin-bottom: 1rem;
    color: var(--md-typeset-color);
}
.intro-links {
    margin-top: 2rem;
    display: grid;
    grid-template-columns: repeat(2, 1fr);
    gap: 1rem;
    font-size: 1.1rem;
    max-width: 360px;
}
.intro-links a {
    text-decoration: none;
    display: inline-flex;
    align-items: center;
    justify-content: center;
    gap: 0.4rem;
    padding: 0.6rem 1rem;
    border-radius: 0.5rem;
    background-color: var(--md-code-bg-color);
    color: var(--md-typeset-color);
    white-space: nowrap;
    transition: background-color 0.2s, color 0.2s;
}
.intro-links a:hover {
    background-color: var(--md-accent-fg-color);
    color: var(--md-accent-bg-color);
}
.showcase-container {
    width: 100%;
    max-width: 400px;
    margin: 0 auto;
}
@media screen and (max-width: 900px) {
    .homepage-wrapper {
        text-align: center;
    }
    .intro-links {
        margin: 2rem auto 0 auto;
    }
}
</style>

<div class="homepage-wrapper">
    <div class="intro-section">
        <h1 style="display: flex; align-items: center; gap: 0.8rem;">
            <img src="logo.png" alt="logo" style="width: 54px; height: 54px; border-radius: 50%;" /> 
            Hi, 欢迎来到 ZJUCSSU!
        </h1>
        <p>这里是 <b>浙江大学计算机科学与技术学院学生会</b> 为服务全体计算机学院同学所搭建的站点。</p>
        
        <p>我们提供重要的高频通知、学习资源的收集与分享、以及同学们和学院之间的一线沟通渠道。</p>

        <p style="margin-top: 2rem; font-size: 0.95rem; opacity: 0.8;">
            <span class="twemoji">
                <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path d="M16.36 14c.08-.66.14-1.32.14-2s-.06-1.34-.14-2h3.38c.16.64.26 1.31.26 2s-.1 1.36-.26 2m-5.15 5.56c.6-1.11 1.06-2.31 1.38-3.56h2.95a8.03 8.03 0 0 1-4.33 3.56M14.34 14H9.66c-.1-.66-.16-1.32-.16-2s.06-1.35.16-2h4.68c.09.65.16 1.32.16 2s-.07 1.34-.16 2M12 19.96c-.83-1.2-1.5-2.53-1.91-3.96h3.82c-.41 1.43-1.08 2.76-1.91 3.96M8 8H5.08A7.92 7.92 0 0 1 12 4.44C11.4 5.55 10.94 6.75 10.62 8M5.08 16H8c.32 1.25.78 2.45 1.38 3.56A7.92 7.92 0 0 1 5.08 16M4.26 14C4.1 13.36 4 12.69 4 12s.1-1.36.26-2h3.38c-.08.66-.14 1.32-.14 2s.06 1.34.14 2M12 4.04c.83 1.2 1.5 2.54 1.91 3.96h-3.82c.41-1.42 1.08-2.76 1.91-3.96m2.62 3.96c.32-1.25.78-2.45 1.38-3.56A7.92 7.92 0 0 1 18.92 8z"/></svg>
            </span>
            <a href="https://github.com/ZJU-CSSU-Dev/home" target="_blank" style="color: inherit;"><b>GitHub</b></a> &nbsp;/&nbsp;
            <span class="twemoji">
                <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path d="M15.5 1h-8C6.12 1 5 2.12 5 3.5v17C5 21.88 6.12 23 7.5 23h8c1.38 0 2.5-1.12 2.5-2.5v-17C18 2.12 16.88 1 15.5 1zm-4 21c-.83 0-1.5-.67-1.5-1.5s.67-1.5 1.5-1.5 1.5.67 1.5 1.5-.67 1.5-1.5 1.5zm4.5-4H7V4h9v14z"/></svg>
            </span>
            <a href="https://www.wjx.cn/vm/wc5HPAS.aspx" target="_blank" style="color: inherit;"><b>点我反馈</b></a>
        </p>

        <div class="intro-links">
            <a href="./Notification/index.html">
                <span class="twemoji">
                    <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path d="M21 19v1H3v-1l2-2v-6c0-3.1 2.03-5.83 5-6.71V4a2 2 0 0 1 2-2 2 2 0 0 1 2 2v.29c2.97.88 5 3.61 5 6.71v6l2 2m-7 2a2 2 0 0 1-2 2 2 2 0 0 1-2-2h4z"/></svg>
                </span> 通知中心
            </a>
            <a href="./知识共享/index.html">
                <span class="twemoji">
                    <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path d="M12 3C7.58 3 4 4.79 4 7s3.58 4 8 4 8-1.79 8-4-3.58-4-8-4m0 5.5c-3.53 0-6.43-1.04-7.5-2.5C5.57 4.54 8.47 3.5 12 3.5s6.43 1.04 7.5 2.5c-1.07 1.46-3.97 2.5-7.5 2.5zM4 9.1c1.55 1.34 4.29 2.4 8 2.4s6.45-1.06 8-2.4v2.9c0 2.21-3.58 4-8 4s-8-1.79-8-4V9.1m0 5.4c1.55 1.34 4.29 2.4 8 2.4s6.45-1.06 8-2.4v2.9c0 2.21-3.58 4-8 4s-8-1.79-8-4v-2.9z"/></svg>
                </span> 知识共享
            </a>
            <a href="./答疑解惑/index.html">
                <span class="twemoji">
                    <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path d="M11 18h2v-2h-2v2m1-16C6.48 2 2 6.48 2 12s4.48 10 10 10 10-4.48 10-10S17.52 2 12 2zm0 18c-4.41 0-8-3.59-8-8s3.59-8 8-8 8 3.59 8 8-3.59 8-8 8zm0-14c-2.21 0-4 1.79-4 4h2c0-1.1.9-2 2-2s2 .9 2 2c0 2-3 1.75-3 5h2c0-2.25 3-2.5 3-5 0-2.21-1.79-4-4-4z"/></svg>
                </span> 答疑解惑
            </a>
            <a href="./关于我们/index.html">
                <span class="twemoji">
                    <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path d="M11 9h2V7h-2m1 13c-4.41 0-8-3.59-8-8s3.59-8 8-8 8 3.59 8 8-3.59 8-8 8m0-18A10 10 0 0 0 2 12a10 10 0 0 0 10 10 10 10 0 0 0 10-10A10 10 0 0 0 12 2m-1 15h2v-6h-2v6z"/></svg>
                </span> 关于我们
            </a>
        </div>
    </div>
    
    <div class="showcase-container">
        <div id="app"></div>
    </div>
</div>

<script type="module" crossorigin src="assets/cards/assets/index.acbe45c2.js"></script>

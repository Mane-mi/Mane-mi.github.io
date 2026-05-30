---
layout: default
title: 关于
---

<div class="container container-narrow">
    <header class="page-header">
        <h1>关于我</h1>
    </header>

    <div class="about-content">
        <!-- 头像占位 -->
        <div class="about-avatar">
            🌸
        </div>

        <div class="about-intro">
            <h2>你好，我是 {{ site.author }}</h2>

            <p>
                这是一个用 Jekyll 搭建的小清新博客。我热爱生活，喜欢记录和分享。
            </p>

            <p>
                在这里，你可以找到关于：
            </p>

            <ul style="text-align: left; display: inline-block; margin: 1rem 0;">
                <li>💡 技术学习心得</li>
                <li>📚 读书笔记</li>
                <li>🌈 生活感悟</li>
                <li>🎨 创意作品</li>
            </ul>

            <p>
                感谢你的来访，希望这些文字能给你带来一点点温暖。
            </p>

            <hr style="border: none; border-top: 1px solid var(--color-bg-secondary); margin: 2rem 0;">

            <h3>联系方式</h3>

            <div class="footer-links mt-md">
                <a href="https://github.com" target="_blank">GitHub</a>
                <a href="mailto:example@email.com">Email</a>
                <a href="{{ '/feed.xml' | relative_url }}">RSS</a>
            </div>
        </div>
    </div>
</div>

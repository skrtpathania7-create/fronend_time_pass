# fronend_time_pass
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Q-Quntum - Tech news spot</title>
    <link rel="stylesheet" href="styles.css">
</head>

<body>

    <header>
        <header class="main-header">
            <form class="search-form" action="/search" method="get">
                <label for="search-input" class="visually-hidden">Search the site</label>

                <input type="search" id="search-input" name="q" placeholder="Search Q-Quntum..." required>

                <button type="submit">
                    🔍 Search
                </button>
            </form>
        </header>

        <div class="container">
            <h1>Q-Quntum</h1>
            <nav>
                <ul>
                    <li><a href="#intro">Introduction</a></li>
                    <li><a href="#ai">Artificial Intelligence</a></li>
                    <li><a href="#data">Data Science</a></li>
                    <li><a href="https://www.bloomberg.com/asia" target="_blank">Latest News</a></li>
                </ul>
            </nav>
        </div>
    </header>

    <main>

        <section id="intro" class="hero">
            <div class="container">
                <h2>Deep Dive into Modern Tech Topics</h2>
                <p>Explore the frontiers of technology with our latest blog series. We break down complex concepts into
                    digestible insights.</p>
            </div>
        </section>

        <section id="ai" class="topic-section">
            <div class="container">
                <h2>🤖 Topic 1: Artificial Intelligence & ML</h2>
                <p>Understand how Neural Networks function and the latest breakthroughs in Generative AI.</p>
                <ul class="key-points">
                    <a href="https://en.wikipedia.org/wiki/Machine_learning" target="_blank">
                        <li>What are key fetures of AI and Machine Learing
                    </a></li>
                    <a href="https://www.nature.com/articles/s43588-025-00890-x" target="_blank">
                        <li>The Rise of Large Language Models (LLMs)
                    </a></li>
                    <a href="https://www.unesco.org/en/artificial-intelligence/recommendation-ethics" target="_blank">
                        <li>Ethics in AI development
                    </a></li>
                </ul>
            </div>
        </section>

        <section id="webdev" class="topic-section ">
            <div class="container">
                <h2>🌐 Topic 2: Modern Web Development</h2>
                <p>How far technology has come, from a simple python program to exploxive LLM's</p>
                <div class="blog-card">
                    <h3>Frontend vs. Backend</h3>
                    <p>A comparison of client-side rendering and server-side logic.</p>
                    <a href="https://www.google.com/search?sca_esv=7ae05214eb9d467f&sxsrf=AE3TifMj3_RwOt-4eg-d8O5suuev7eqbuw:1763630156471&udm=7&fbs=AIIjpHxU7SXXniUZfeShr2fp4giZ1Y6MJ25_tmWITc7uy4KIeiAkWG4OlBE2zyCTMjPbGmPgfe_7ak8LUsonpWCvT6w6csnyTymMQ2XHqFKxVhyiTmJzj3oNuYO0xVDYaPC8i64NYg-h8nhIId6bG_YuNz6V9C6hGHy1KW3_1Vg28xnv8tT3KNlJIAt2DSaFcbqnYQvqwSiXpg3FGfvIvjRJl0cxxx1xHA&q=frontend+and+backend&sa=X&ved=2ahUKEwjl7fansoCRAxV_zTgGHSA7CHoQtKgLegQIFhAB&biw=1536&bih=730&dpr=1.25#fpstate=ive&vld=cid:e4b3729e,vid:oVC-RQ2Nxds,st:0"
                        target="_blank">Info. on Frontend and Backend</a>
                </div>
                <div class="blog-card">
                    <h3>The Power of CSS and HTML in frontend</h3>
                    <p>Advanced layout techniques for responsive design.</p>
                    <a href="https://www.google.com/search?q=html+and+css+for+beginners&sca_esv=7ae05214eb9d467f&udm=7&biw=1536&bih=730&sxsrf=AE3TifOVT0aknxAvb3Ze4MFqdzc8YTbwOQ%3A1763630390761&ei=Nt0eaeOULv_0juMPy8K22Aw&oq=html+and+css+for&gs_lp=EhZnd3Mtd2l6LW1vZGVsZXNzLXZpZGVvIhBodG1sIGFuZCBjc3MgZm9yKgIIADILEAAYgAQYkQIYigUyCxAAGIAEGJECGIoFMgUQABiABDIFEAAYgAQyBRAAGIAEMgUQABiABDIFEAAYgAQyCxAAGIAEGIYDGIoFMgsQABiABBiGAxiKBTILEAAYgAQYhgMYigVIyRhQmAFY5w1wAXgBkAEAmAH_AaAB1QaqAQUwLjIuMrgBAcgBAPgBAZgCBaAC6QbCAgoQABiwAxjWBBhHwgIKEAAYgAQYQxiKBcICChAAGIAEGBQYhwKYAwCIBgGQBgiSBwUxLjIuMqAH3RiyBwUwLjIuMrgH5AbCBwUwLjMuMsgHDw&sclient=gws-wiz-modeless-video#fpstate=ive&vld=cid:b00768f8,vid:qz0aGYrrlhU,st:0"
                        target="_blank">HTML and css crash course</a>
                </div>
            </div>
        </section>

        <section id="data" class="topic-section">
            <div class="container">
                <h2>📊 Topic 3: Data Science & Analytics</h2>
                <p>Learn how transformers work and how reserchers got them in working conditionds.</p>
                <p>Read the paper that they published on this topic which created a stir in the market!</p>
                <a href="https://en.wikipedia.org/wiki/Attention_Is_All_You_Need" class="cta-button"
                    target="_blank">Attention is all you need</a>
            </div>
        </section>


    </main>

    <footer>
        <div class="container">
            <p>Q-Quntum | &copy; 2025</p>
        </div>
    </footer>

</body>

</html>

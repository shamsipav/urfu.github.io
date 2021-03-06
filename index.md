<!DOCTYPE html>
<html lang="ru">
    <head>
        <meta charset="UTF-8" />
        <meta http-equiv="X-UA-Compatible" content="IE=edge" />
        <meta name="viewport" content="width=device-width, initial-scale=1.0" />
        <title>Магистратура</title>
        <link rel="stylesheet" href="css/style.css" />
    </head>
    <body>
        <header class="header">
            <div class="header__container container">
                <img class="header__logo" src="img/logo_urfu.svg" alt="logo_urfu" />
                <nav class="menu">
                    <ul class="menu__list">
                        <li class="menu__item"><a href="#" class="menu__link">Об институте</a></li>
                        <li class="menu__item"><a href="#" class="menu__link">Как поступить</a></li>
                        <li class="menu__item"><a href="#" class="menu__link">Программы</a></li>
                        <li class="menu__item"><a href="#" class="menu__link">FAQ</a></li>
                        <li class="menu__item"><a href="#" class="menu__link">Контакты</a></li>
                    </ul>
                </nav>
                <button class="header__button button">Хочу поступить</button>
            </div>
        </header>
        <section class="main">
            <div class="main__container container">
                <div class="main__content">
                    <div class="main__head">
                        <h1 class="main__heading">Магистратура</h1>
                        <p class="main__description">Химико-технологический<br />институт УрФУ</p>
                    </div>
                    <div class="main__education education">
                        <p class="education__description">
                            Практико-ориентированное образование через прикладную<br />
                            и фундаментальную науку<br />
                            мирового уровня
                        </p>
                        <a href="#" class="education__programs">Смотреть программы</a>
                    </div>
                </div>
                <img class="main__blur-left" src="img/main_blur.png" alt="main_blur-left" />
                <img class="main__blur-right" src="img/main_blur.png" alt="main_blur-right" />
                <img class="main__line" src="img/main_line.svg" alt="main_line" />
            </div>
        </section>
        <section class="about">
            <div class="about__container container">
                <div class="about__info">
                    <h2 class="about__heading">Об институте</h2>
                    <p class="about__description">
                        ХТИ - это глубокие научные и образовательные традиции, а также высококвалифицированные сотрудники, обладающие богатым опытом в решении разноплановых фундаментальных и
                        прикладных задач в области современной химии и химической технологии.
                    </p>
                    <a href="#" class="about__site">Посетить сайт института</a>
                    <button class="about__join button">Поступить</button>
                </div>
                <div class="about__content">
                    <div class="about__videos">
                        <img class="about__video" src="img/about_film-1.png" alt="about_film-1" />
                        <img class="about__video" src="img/about_film-2.png" alt="about_film-2" />
                    </div>
                    <ul class="about__features">
                        <li class="about__features-item item-features">
                            <span class="item-features__value">25</span>
                            <p class="item-features__description">Российских и зарубежных академических партнеров</p>
                        </li>
                        <li class="about__features-item item-features">
                            <span class="item-features__value">20</span>
                            <p class="item-features__description">
                                Крупных индустриальных<br />
                                партнеров
                            </p>
                        </li>
                        <li class="about__features-item item-features">
                            <span class="item-features__value">150</span>
                            <p class="item-features__description">Бюджетных мест по программам магистратуры</p>
                        </li>
                    </ul>
                </div>
            </div>
        </section>
        <section class="instruction">
            <div class="instruction__container container">
                <div class="instruction__head">
                    <h2 class="instruction__heading">Как поступить?</h2>
                    <div class="instruction__toggle">
                        <span id="budget" class="checked">Бюджет</span>
                        <div class="instruction__switch">
                            <input type="checkbox" id="switch" />
                            <label for="switch">Toggle</label>
                        </div>
                        <span id="contract">Контракт</span>
                    </div>
                </div>
                <div class="instruction__main">
                    <div id="budgetEducationContent" class="instruction__content show">
                        <ul class="instruction__step step-instruction">
                            <li class="step-instruction__item">
                                <span class="step-instruction__number">1</span>
                                <p class="step-instruction__heading">Узнайте о поступлении</p>
                            </li>
                            <li class="step-instruction__item">
                                <p class="step-instruction__item-title">Правила приема</p>
                            </li>
                            <li class="step-instruction__item">
                                <p class="step-instruction__item-title">Сроки подачи документов</p>
                                <div class="step-instruction__item-schedule">
                                    <p>Очная форма обучения:</p>
                                    <span>20.06 - 08.08</span>
                                </div>
                                <div class="step-instruction__item-schedule">
                                    <p>Очно-заочная форма обучения:</p>
                                    <span>20.06 - 08.08</span>
                                </div>
                            </li>
                        </ul>
                        <ul class="instruction__step step-instruction">
                            <li class="step-instruction__item">
                                <span class="step-instruction__number">2</span>
                                <p class="step-instruction__heading">Выберите образовательную программу</p>
                            </li>
                            <li class="step-instruction__item">
                                <p class="step-instruction__item-title">Каталог образовательных программ</p>
                            </li>
                            <li class="step-instruction__item">
                                <a href="#" class="step-instruction__programs">Смотреть программы</a>
                            </li>
                        </ul>
                        <ul class="instruction__step step-instruction">
                            <li class="step-instruction__item">
                                <span class="step-instruction__number">3</span>
                                <p class="step-instruction__heading">Подайте документы</p>
                            </li>
                            <li class="step-instruction__item">
                                <p class="step-instruction__item-title">Подать документы онлайн через личный кабинет абитуриента</p>
                            </li>
                            <li class="step-instruction__item">
                                <a href="#" class="step-instruction__registration">Регистрация</a>
                            </li>
                        </ul>
                        <ul class="instruction__step step-instruction">
                            <li class="step-instruction__item">
                                <span class="step-instruction__number">4</span>
                                <p class="step-instruction__heading">Пройдите вступительные испытания</p>
                            </li>
                            <li class="step-instruction__item">
                                <p class="step-instruction__item-title">Период сдачи вступительных испытаний</p>
                                <div class="step-instruction__item-schedule budget">
                                    <p>Очная форма обучения:</p>
                                    <span>20.06 - 08.08</span>
                                </div>
                                <div class="step-instruction__item-schedule budget">
                                    <p>Очно-заочная форма обучения:</p>
                                    <span>04.07 - 13.09 и 22.08 - 12.09</span>
                                </div>
                            </li>
                        </ul>
                    </div>
                    <div id="contractEducationContent" class="instruction__content">
                        <ul class="instruction__step step-instruction">
                            <li class="step-instruction__item">
                                <span class="step-instruction__number">1</span>
                                <p class="step-instruction__heading">Узнайте о поступлении</p>
                            </li>
                            <li class="step-instruction__item">
                                <p class="step-instruction__item-title">Правила приема</p>
                            </li>
                            <li class="step-instruction__item">
                                <p class="step-instruction__item-title">Сроки подачи документов</p>
                                <div class="step-instruction__item-schedule">
                                    <p>Очная форма обучения:</p>
                                    <span>20.06 - 23.09</span>
                                </div>
                                <div class="step-instruction__item-schedule">
                                    <p>Очно-заочная форма обучения:</p>
                                    <span>20.06 - 28.10</span>
                                </div>
                            </li>
                        </ul>
                        <ul class="instruction__step step-instruction">
                            <li class="step-instruction__item">
                                <span class="step-instruction__number">2</span>
                                <p class="step-instruction__heading">Выберите образовательную программу</p>
                            </li>
                            <li class="step-instruction__item">
                                <p class="step-instruction__item-title">Каталог образовательных программ</p>
                            </li>
                            <li class="step-instruction__item">
                                <a href="#" class="step-instruction__programs">Смотреть программы</a>
                            </li>
                        </ul>
                        <ul class="instruction__step step-instruction">
                            <li class="step-instruction__item">
                                <span class="step-instruction__number">3</span>
                                <p class="step-instruction__heading">Подайте документы</p>
                            </li>
                            <li class="step-instruction__item">
                                <p class="step-instruction__item-title">Подать документы онлайн через личный кабинет абитуриента</p>
                            </li>
                            <li class="step-instruction__item">
                                <a href="#" class="step-instruction__registration">Регистрация</a>
                            </li>
                        </ul>
                        <ul class="instruction__step step-instruction">
                            <li class="step-instruction__item">
                                <span class="step-instruction__number">4</span>
                                <p class="step-instruction__heading">Пройдите вступительные испытания</p>
                            </li>
                            <li class="step-instruction__item">
                                <p class="step-instruction__item-title">Период сдачи вступительных испытаний</p>
                                <div class="step-instruction__item-schedule budget">
                                    <p>Очная форма обучения:</p>
                                    <span>04.07 - 13.08 и 22.08 - 24.09</span>
                                </div>
                                <div class="step-instruction__item-schedule budget">
                                    <p>Очно-заочная форма обучения:</p>
                                    <span>04.07 - 13.08 и 22.08 - 29.10</span>
                                </div>
                            </li>
                        </ul>
                    </div>
                </div>
            </div>
        </section>
        <footer class="footer"></footer>
        <script src="script/script.js"></script>
    </body>
</html>

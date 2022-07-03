# Navbar
Адаптивное меню: https://getbootstrap.com/docs/5.2/components/navbar/. Многое можно изменять: цвет, элементы, положение и мн.др.

Контейнер обычно помещают внутрь тега `nav`:

    <!-- navbar -->
    <nav class="navbar navbar-expand-md bg-light">
        <div class="container">
            <a class="navbar-brand" href="#intro"><span class="fw-bold text-secondary">Brand</span></a>
            <!-- toggle button for mobile nav -->
            <button class="navbar-toggler" type="button"
                data-bs-toggle="collapse"
                data-bs-target="#main-nav">
                <span class="navbar-toggler-icon"></span>
            </button>
            <!-- navbar links -->
            <div class="collapse navbar-collapse justify-content-end align-center" id="main-nav">
                <ul class="navbar-nav">
                    <li class="nav-item">
                        <a class="nav-link" href="#topics">About</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#reviews">Reviews</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#contact">Contact</a>
                    </li>
                    <li class="nav-item d-md-none">
                        <a class="nav-link" href="#pricing">Pricing</a>
                    </li>
                    <li class="nav-item ms-2 d-none d-md-inline">
                        <a class="btn btn-secondary" href="#pricing">Buy now</a>
                    </li>
                </ul>
            </div>
        </div>
    </nav>

В `nav` можно поместить класс `navbar-dark bg-primary` чтобы изменить фон меню или добавить класс `fixed-bottom` чтобы зафиксировать меню снизу.

<template>
    <nav class="navbar bg-dark navbar-expand-lg" data-bs-theme="dark">
        <div class="container">
            <RouterLink class="navbar-brand" to="/">Bucklify</RouterLink>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarSupportedContent">
                <ul class="navbar-nav ms-auto mb-2 mb-lg-0">
                    <li class="nav-item dropdown">
                        <a class="nav-link dropdown-toggle" href="#" role="button" data-bs-toggle="dropdown" aria-expanded="false">
                            Profile
                        </a>
                        <ul class="dropdown-menu dropdown-menu-end">
                            <li>
                                <RouterLink class="dropdown-item" to="/login">Login</RouterLink>
                            </li>
                            <li>
                                <RouterLink class="dropdown-item" to="/signup">Sign Up</RouterLink>
                            </li>
                        </ul>
                    </li>
                </ul>
            </div>
        </div>
    </nav>
</template>
cmake_minimum_required(VERSION 3.8)
project(PT_Website)

set(CMAKE_CXX_STANDARD 11)

set(SOURCE_FILES
        css/bootstrap-theme.min.css
        css/bootstrap.min.css
        css/font-awesome.min.css
        css/linearicons-web-font.css
        css/main.css
        css/responsive.css
        fonts/fontawesome-webfont.eot
        fonts/fontawesome-webfont.svg
        fonts/fontawesome-webfont.ttf
        fonts/fontawesome-webfont.woff
        fonts/fontawesome-webfont.woff2
        fonts/FontAwesome.otf
        fonts/glyphicons-halflings-regular.eot
        fonts/glyphicons-halflings-regular.svg
        fonts/glyphicons-halflings-regular.ttf
        fonts/glyphicons-halflings-regular.woff
        fonts/lato-regular.woff2
        fonts/Linearicons-Free.eot
        fonts/Linearicons-Free.svg
        fonts/Linearicons-Free.ttf
        fonts/Linearicons-Free.woff
        fonts/Linearicons-Free.woff2
        fonts/nightstillcomes_bold_final_sample.woff2
        fonts/nightstillcomes_mine_final_sample.woff2
        fonts/stackyard_personal_use-webfont.woff2
        img/chair2.jpg
        img/header_bg2.jpg
        img/keyboard2.jpg
        img/loading.gif
        img/pf1.jpg
        img/pf2.jpg
        img/pf3.jpg
        img/pf4.jpg
        img/pf5.jpg
        img/pf6.jpg
        js/vendor/bootstrap.min.js
        js/vendor/jquery-1.11.2.min.js
        js/vendor/modernizr-2.8.3-respond-1.4.2.min.js
        js/main.js
        js/masonry.pkgd.min.js
        index.html
        "Read me.txt")

add_executable(PT_Website ${SOURCE_FILES})
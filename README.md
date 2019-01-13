# Топосьемка пещеры Слизняк

## Компиляция в программе Therion

Топосёмка проводилась при помощи прибора DistoX и программы TopoDroid для системы Android. TopoDroid записывает измерения полученные из DistoX и карту сразу в формате программы Therion, который позваляет добавлять дополнительные подробности, править карту и производит оконьчательные версии карты, разреза, модели и так далее в формате PDF.

### Подготовка Therion

Программа Therion работает под системой Linux и есть доступна во всех ег дистрибуциях. 

Файль 

    pdf-fonts /usr/share/fonts/truetype/ttf-dejavu/DejaVuSerifCondensed.ttf /usr/share/fonts/truetype/ttf-dejavu/DejaVuSerifCondensed-Italic.ttf /usr/share/fonts/truetype/ttf-dejavu/DejaVuSerifCondensed-Bold.ttf /usr/share/fonts/truetype/ttf-dejavu/DejaVuSansCondensed.ttf /usr/share/fonts/truetype/ttf-dejavu/DejaVuSansCondensed-Oblique.ttf

    sudo apt install ttf-dejavu-extra therion
    echo pdf-fonts "/usr/share/fonts/truetype/ttf-dejavu/DejaVuSerif.ttf" \
        "/usr/share/fonts/truetype/ttf-dejavu/DejaVuSerif-Italic.ttf" \
        "/usr/share/fonts/truetype/ttf-dejavu/DejaVuSerif-Bold.ttf" \
        "/usr/share/fonts/truetype/ttf-dejavu/DejaVuSans.ttf" \
        "/usr/share/fonts/truetype/ttf-dejavu/DejaVuSans-Oblique.ttf" \
        > ~/.therion/therion.ini

Компиляция карты:

    therion thconfig
    

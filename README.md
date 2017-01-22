# Топосьемка пещеры Слизняк Edit

Подготовка программы Therion под Линуксом:

    sudo apt install ttf-dejavu-extra therion
    echo pdf-fonts "/usr/share/fonts/truetype/ttf-dejavu/DejaVuSerif.ttf" \
        "/usr/share/fonts/truetype/ttf-dejavu/DejaVuSerif-Italic.ttf" \
        "/usr/share/fonts/truetype/ttf-dejavu/DejaVuSerif-Bold.ttf" \
        "/usr/share/fonts/truetype/ttf-dejavu/DejaVuSans.ttf" \
        "/usr/share/fonts/truetype/ttf-dejavu/DejaVuSans-Oblique.ttf" \
        > ~/.therion/therion.ini

Компиляция карты:

    therion thconfig
    

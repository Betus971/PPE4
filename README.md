# PPE4
installer et creation de symfony 
sudo apt install composer 
****************installer PHP*****************
si vous avez la dernier version de ubuntu c'est du 8.3 votre PHP


apt-get install php8.3 libapache2-mod-php8.3 php8.3-common php8.3-gd php8.3-mysql php8.3-curl php8.3-intl php8.3-xsl php8.3-mbstring php8.3-zip php8.3-bcmath php8.3-soap php-xdebug php-imagick


si c'est pas le cas remplacer le le 8.3 part 8.2 ou 8.1 tout depend de votre version linux


composer create-project symfony/skeleton:"7.1.*" monprojet


cd monprojet


composer require webapp


php -S localhost:8000 -t public





et vous avez votre symfony 

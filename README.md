=================================================

������ ���������, �������������� �������
----------------------------------------

��������� ���������:

    php -r "readfile('https://getcomposer.org/installer');" | php

��������� ��������:

    php composer.phar install

��������� ����:

    php app/console doctrine:database:create

��������� ����������� ��� ������ ���� ��� ����� ���� � �����:

    php app/console chmod -R 0777 app/cache/

    php app/console chmod -R 0777 app/logs/

����������� ������� ��� ������� ����� ����
------------------------------------------

���������� ��������:

    php composer.phar install

���������� ����:

    php app/console doctrine:schema:update --force

��������� �������:

    php app/console assets:install --symlink

���������� ��������:

    php app/console assetic:dump --watch

������ �������
--------------

��� ��������� ������� � �� �������� ����� ���������� ��������:

    php app/console

��������� setters � getters:

    php app/console doctrine:generate:entities Vilka/CoreBundle/Entity/ModelName

������ �� ������� ������������
------------------------------

http://symfony-gu.ru/documentation/ru/html/

������ �� ��� ����
------------------
[1]:  http://symfony.com/doc/2.4/book/installation.html
[2]:  http://getcomposer.org/
[3]:  http://symfony.com/download
[4]:  http://symfony.com/doc/2.4/quick_tour/the_big_picture.html
[5]:  http://symfony.com/doc/2.4/index.html
[6]:  http://symfony.com/doc/2.4/bundles/SensioFrameworkExtraBundle/index.html
[7]:  http://symfony.com/doc/2.4/book/doctrine.html
[8]:  http://symfony.com/doc/2.4/book/templating.html
[9]:  http://symfony.com/doc/2.4/book/security.html
[10]: http://symfony.com/doc/2.4/cookbook/email.html
[11]: http://symfony.com/doc/2.4/cookbook/logging/monolog.html
[12]: http://symfony.com/doc/2.4/cookbook/assetic/asset_management.html
[13]: http://symfony.com/doc/2.4/bundles/SensioGeneratorBundle/index.html

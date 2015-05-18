# Unitemplate - ����� ��� ���������� ��������

��������� ������������� �������

### ��������

����������� ����������:
* php >= 5.4
* git ([���������](http://git-scm.com/book/ru/v2/%D0%92%D0%B2%D0%B5%D0%B4%D0%B5%D0%BD%D0%B8%D0%B5-%D0%A3%D1%81%D1%82%D0%B0%D0%BD%D0%BE%D0%B2%D0%BA%D0%B0-Git))

#### ���� �� ���������

 1. ������� ������ ����������
 ```sh
 $ git clone [git-repo-url]
 $ cd unitemplate
 ```
 ��� [git-repo-url] - ������� url �����������

 2. ��������� �������� �������
 ```sh
 $ php composer.phar install --no-dev
 ```
 
 3. ��� ������������� ��������� ����� �� ������ ��� �����
 ```sh
 $ chmod -R 777 app/lib/tpl/tpl_compiled/
 ```

 4. ��������� ����������
 ```sh
 $ php -S localhost:8008
 ```
 
 5. ������� ���������� � �������� [http://localhost:8008](http://localhost:8008)
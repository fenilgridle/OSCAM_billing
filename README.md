oscam_billing
============

1. ���������

���������� ������� pip � virtualenv (� ����� ����� ��������).
����� ����� ���������� mongodb

���������� ����� ���������� xpresscredit �������� ��������� �����������, � ������� ��� ���������� ����
��� ����� ������� � �������������� � ������� ����� � ��������, ������

virtualenv --no-pip --no-setuptools env

��������� --no-pip --no-setuptools ������������ ��� �����, ��� � ��������� ����� �� 7-� �����. ����� ����� ������� ����� ����� ���������� pip
��� ������� ����� ����� �� �����.

source env/bin/activate

� ����� ������ ��� ����:
��� ��������� ������:

pip install -r requirements/local.txt

��� ���������:

pip install -r requirements/production.txt

������. �������� ��������� ������. ��� ����� ������� � ����� xpress

manager.py runserver --settings=settings.local


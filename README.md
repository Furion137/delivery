## Customer feature
>������ ���������� ������� ���������� ���������� (��������, ���������, ���������, ��������) ��������� ��������� � ���� ������.

*���������� �� �������:*
- [**Entity**](#entity)
- [**Dao**](#dao)
- **Service**
- **Controller**
_____

### <a name="entity">Entity</a>
>����������� Entity �������� **Customer.java**. ������ ����� ��������� �������� ���������, ������� ���������� @Entity, ����� ��������� ����, ���������� ��������� ������� customers, ������ � ������� ����������� � ������� ������� � ��������.
##### ����� *Customer.java* �������� ��������� ����:
1. ***id** - (������ private, ��� long) ������������� ���������� ����������������� ����� ���������. �������� ��������� ������ ������� customers. �� ����� ����� �������� ��������. ������������������� �� ������� ����������. ����� ����������������� ��� ������� **"customer_id"** � ������� customers.*
2. ***name** - (������ private, ��� String) �������� ������������ ���������.*
3. ***address** - (������ private, ��� String) �������� ����� ���������. �� ����� ����� �������� ��������.*
4. ***phoneNumber** - (������ private, ��� String) �������� ����� �������� ���������. �� ����� ����� �������� ��������. ����� ����������������� ��� ������� **"phone_number"** � ������� customers. �������� ������ ���������� ������.*
5. ***eMail** - (������ private, ��� String) �������� ����� ����������� ����� ���������. �� ����� ����� �������� ��������. ����� ����������������� ��� ������� **"e_mail"** � ������� customers. �������� ������ ���������� ������.*

##### ����� *Customer.java* ����� ������:
###### *�������:*
- ***public void setId(Long id)** - ������ ��� ���� **id**.* 
- ***public void setName(String name)** - ������ ��� ���� **name**.*
- ***public void setAddress(String address)** - ������ ��� ���� **address**.*
- ***public void setPhoneNumber(String phoneNumber)** - ������ ��� ���� **phoneNumber**.*
- ***public void seteMail(String eMail)** - ������ ��� ���� **eMail**.*
>������� ������ �������� ���������������� ���� ������ ������ ����������� � ��� �������� ���������.
###### *�������:*
- ***public long getId()** - ������ ��� ���� **id**.*
- ***public String getName()** - ������ ��� ���� **Name**.*
- ***public String getAddress()** - ������ ��� ���� **Address**.*
- ***public String getPhoneNumber()** - ������ ��� ���� **PhoneNumber**.*
- ***public String geteMail()** - ������ ��� ���� **eMail**.*
>������� ���������� �������� ���������������� ���� ������.

______

### <a name="dao">DAO</a>
> DAO ���� ��������������� ��������������� � ����� ������. 
###### *�������� � ���� ����������:*
- ***BasicDao** - �������� ���������, ����������� ������� CRUD-��������.*
- ***CustomerDao** - ���������, �������������� �� BasicDao � ����������� ��� ���������� ��������������� �������� �������������� �������� ��������� � ����� ������*

#### *To be continued...*
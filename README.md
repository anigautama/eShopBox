# eshopbox
Eshopbox Assignment



# Project Title

Eshopbox Ticket Assignment App

## Getting Started

In Eshopticket Assignment you can

1. Create A Ticket
2. Assign a ticket
3. Close a ticket.
4. find open tickets for a department
5. find open tickets for a manager.

# Features
* Only super user can view all ticket
* Employee can view his created ticket or assigned ticket
* Employee can change the status
* Ticket can be filtered by Status, Department, AssignedTo,
* Employee can login with his credentials

* Admin can create more employee as authenticate user
* Admin can create Department
* Admin can create Designations
* Admin can assign Designations to Employee


### Prerequisites

What things you need to install the software and how to install them
 * first install pip on system windows or linux
 * using pip install ---   /* with this command you can install all requirement*/
* Django==2.0.5
* django-filter==1.1.0
* mysqlclient==1.3.12
* pytz==2018.4
* MySql 5.6
* PyCharm IDE
* for more info please run pip freeze > requirement.txt

* eshop_db.sql just import into mysql

# set mysql db

* DATABASES = {
    'default': {
        'ENGINE': 'django.db.backends.mysql',
        'NAME': 'eshop_db',
        'USER': 'root',
        'PASSWORD': '',
        'HOST': 'localhost',
        'PORT': 3306,
        'OPTIONS': {'init_command': 'SET default_storage_engine=INNODB', }
    }
}

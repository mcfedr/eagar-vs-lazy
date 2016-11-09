# eagar vs lazy

## How to

composer install
./bin/console hautelook_alice:fixtures:load
./bin/console server:run
GET http://127.0.0.1:8000/employee/

## Places to look

`AppBuilder\Entity\Employee` - try changing EAGAR, LAZY etc on the company relationship

`EmployeeController` GET /  - try changing findAll to QueryBuilder

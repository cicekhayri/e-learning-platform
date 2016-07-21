## E-Learning platform built with Django

* Enroll Course
* Create Subject
* Create Course
* Upload Files, Images, Videos

## API
* List Subjects

curl http://127.0.0.1:8000/api/subjects/

* Enroll course

curl -i -X POST -u student:password http://127.0.0.1:8000/api/courses/1/enroll/

* Course Content

http://127.0.0.1:8000/api/courses/1/contents/
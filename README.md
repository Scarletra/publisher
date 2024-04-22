a. How many data your publlsher program will send to the message broker in one run?

Program akan mengirimkan 5 pesan dalam sekali jalan karena terdapat 5 kali pemanggilan method publish_event dengan UserCreatedEventMessage yang terdapat pada fungsi main.

b. The url of: “amqp://guest:guest@localhost:5672” is the same as in the subscriber program, what does it mean?

Hal ini menandakan bahwa program terkoneksi antara subscriber dengan publisher melalui message broker yang sama. URL ini berguna untuk membuat sebuah antrian publisher yang baru.

![RabbitMQ](image.png)
![RabbitMQ multiple publisher](image-1.png)
Spike pada chart di atas terjadi karena menjalankan publisher berkali-kali

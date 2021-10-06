# Hosted Payment Sample
Contains a sample demo application to provide an example integration of Payment Form.

## Getting Started
1. Install Docker
1. Clone the HostedPayment
1. Build and run the Docker container.

    ```
    docker build -t webserver .
    docker run -dit --name my-webserver -p 8080:80 webserver
    ```
1. Browse `http://localhost:8080/`

## References
* [WorldPay Payment Page Integration - JavaScript SDK](https://developer.worldpay.com/docs/wpg/hostedintegration/javascriptsdk)
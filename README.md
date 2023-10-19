# Setting up Stripe Subscriptions with Flask

## Want to learn how to build this?

Check out the [post](https://testdriven.io/blog/flask-stripe-subscriptions/).

## Want to use this project?

1. Fork/Clone

1. Create and activate a virtual environment:

    ```sh
    python3 -m venv venv && source venv/bin/activate
    ```

1. Install the requirements:

    ```sh
    pip install -r requirements.txt
    ```

1. Add your Stripe test secret key, test publishable key, endpoint secret and price API ID as environmental variables:

    ```sh
    export STRIPE_PUBLISHABLE_KEY=<YOUR_STRIPE_PUBLISHABLE_KEY>
    export STRIPE_SECRET_KEY=<YOUR_STRIPE_SECRET_KEY>
    export STRIPE_PRICE_ID=<YOUR_PRICE_API_ID>
    export STRIPE_ENDPOINT_SECRET=<YOUR_ENDPOINT_SECRET_KEY>
    ```

1. Run the server:

    ```sh
    FLASK_ENV=development python app.py
    ```

    Navigate to [http://localhost:5000](http://localhost:5000).

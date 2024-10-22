# تمپلیت های سابسکریپشن برای مرزنشین

## بررسی

در اینجا ما تمپلیت های سابسکریپشن مرزنشین رو قرار میدیم.
برای بررسی مرزنشین به سایت آن مراجعه کنید([لینک](https://github.com/marzneshin/marzneshin))
برای آموزش نصب قالب ها و یا کسب اطلاعات بیشتر به کانال من سر بزنید ([لینک](https://t.me/MattDevChannel))

## قابلیت ها

- نصب راحت
- آپدیت آسان
- امکان مشاهده حجم ، مشاهده زمان باقیمانده، پشتیبانی و اضافه کردن برنامه ها

## نصب کردن

نصب کردن تمپلیت به طور کلی شامل کپی کردن یک فایل

```text index.html```

در مقصد

```bash /var/lib/marzneshin/templates/subscription/```
هست. سپس در ادامه باید مقادیر زیر رو در فایل .env در پوشه /etc/opt/marzneshin قرار بدین
    ```env  
    CUSTOM_TEMPLATES_DIRECTORY="/var/lib/marzneshin/templates/"
    SUBSCRIPTION_PAGE_TEMPLATE="subscription/index.html"
    ```

یا دستور :

    ```sh
        echo 'CUSTOM_TEMPLATES_DIRECTORY="/var/lib/marzneshin/templates/"' | sudo tee -a /etc/opt/marzneshin/.env
        echo 'SUBSCRIPTION_PAGE_TEMPLATE="subscription/index.html"' | sudo tee -a /etc/opt/marzneshin/.env

    ```
    در ترمینال اجرا کنید

## Usage

To use the templates in your project, follow these steps:

1. Import the necessary files into your project.
2. Customize the templates as needed.
3. Integrate the templates into your application.

## Contributing

We welcome contributions! Please follow these steps to contribute:

1. Fork the repository.
2. Create a new branch:

    ```sh
    git checkout -b feature/your-feature-name
    ```

3. Make your changes and commit them:

    ```sh
    git commit -m "Add your commit message"
    ```

4. Push to the branch:

    ```sh
    git push origin feature/your-feature-name
    ```

5. Open a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contact

For any questions or inquiries, please contact us at [your-email@example.com].

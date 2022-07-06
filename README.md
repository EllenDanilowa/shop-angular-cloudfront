# Shop Angular Cloudfront

- [S3](http://rs-ab-shop-app.s3-website-us-east-1.amazonaws.com/)
- [CloudFront](https://d1ksmh8q66xwc2.cloudfront.net/)

### Commands
- To start the app in dev mode:
  ```bash
  $ npm start
  ```

- To build the app in prod mode:
  ```bash
  $ npm run build
  ```

- To deploy with confirmation:
  ```bash
  $ npm run cloudfront:update:deploy
  ```
  Or without:
  ```bash
  $ npm run cloudfront:update:deploy:nc
  ```

- To see the deployed URL:
  ```bash
  $ npm run cloudfront:domainInfo
  ```

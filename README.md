# S3 SPA Infrastructure CF Template

SPA Application Infrastructure with CloudFront + S3

## Environment

- Route53
- CloudFront
- S3
- WAF

## Directory Design

- root.yml ... Root Stack
- templates/ ... Stacks of SPA Application
- sample/ ... sample index.html

## How to Use

### 1.set your environment variables on .env

.env
```
APP_NAME=sample-spa
DOMAIN_NAME=sample.com
CFSSLCertificateId=xxxx-yyyy-zzzz
```

### 2.login with your AWS account

```
$ aws configure
```

### 3.deploy your service

ENV ... prd | something

```
$ sh deploy ENV
```

### 4. Go To your console and Try it!

enjoy!
![General Assembly Logo](http://i.imgur.com/ke8USTq.png)

# Token authentication in rails

## Objectives

By the end of this lesson, students should be able to:

- Use token authentication to secure a rails based web API

## Introduction

Effective security is broken down into three areas:

- Authentication
- Authorization
- Auditing

### Authentication

Who (or what) is accessing a resource (the principle).

### Authorization

What the principle has access to.

### Auditing

What the principle has actually done

## Authentication in Rails

We'll build a rails api with token based authentiation using rails built-in features.

- http://api.rubyonrails.org/classes/ActiveModel/SecurePassword.html
- http://api.rubyonrails.org/classes/ActionController/HttpAuthentication/Token.html

# Технические задачи

## 1. Цель
SPG_VK.COM - Сервис предоставляет возможность получать фотографии из vk.com по геоданным.

### 1.2 Стек

Backend

    - Symfony 6+
    - PostgreSQL
    - API Platform
    - JWT
    - CRON
  
Frontend

    - Vue 3+

Other cliet

    - Android

## 2. Роли и доступы

## 3. Функцилнал

## 4. Маршуруты

```bash
# 4.1 Guest
/v1/api/ [get] # Get photos count 50

# 4.1.1 Guest/Auth
/v1/api/login [get|post] #login
/v1/api/register [get|post] # registration
/v1/api/reset-pass [get|post] # reste password


# 4.2 User
/v1/api/ [get] # Get photos count 100+
/v1/api/search/{$filter} [post] # Set filter search
/v1/api/search/resault [get] # Get resault search

# 4.2.1 User/Profile
/v1/api/

```

## 5. Клиенты

### 5.1 Web

### 5.2 Android

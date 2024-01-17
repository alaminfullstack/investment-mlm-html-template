# Design 

Here is a complate flow chart:

```mermaid
graph TD;
    Register-->Login;
    Login-->Home;
    Home-->My;
    Home-->Recharge;
    Recharge-->Recharge History;
    Home-->Withdraw;
    Withdraw-->Withdraw History;
    Home-->Team;
    Team-->Team Detail;
    Home-->VIP;
    VIP-->VIP Detail;
    My-->History;
    My-->Recharge History;
    My-->Withdraw History;
    My-->Bank Setting;
    My-->Password Change;
    My-->Logout;
```

### Login

![image info](./readme/login.png)

### Register

![image info](./readme/register.png)

### Account

![image info](./readme/my.png)

### Vip

![image info](./readme/vip.png)

### Vip Detail

![image info](./readme/vip-detail.png)


### Transaction

![image info](./readme/transaction.png)

### Withdraw

![image info](./readme/withdraw.png)

### Home

![image info](./readme/home.png)

### Deposit

![image info](./readme/recharge.png)


### Recharge History

![image info](./readme/history.png)


### My Bank

![image info](./readme/bank.png)


### Team

![image info](./readme/team.png)

### Team Detail

![image info](./readme/team-detail.png)

### Password Change

![image info](./readme/password.png)
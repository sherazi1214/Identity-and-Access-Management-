# Identity-and-Access-Management

##  1. **[Identity & Access Management IAM](https://github.com/sherazi1214/-Identity-Access-Management-IAM/blob/main/README.md)**

## 2. **[Federated Identity FIM](https://github.com/sherazi1214/Federated-Identity-FIM)**

## 3. **[Authentication [Authentication ](https://github.com/sherazi1214/Authentication-)**

## 4. **[Access Control](https://github.com/sherazi1214/Access-Control/blob/main/README.md)**

## 5. Privileged Access Management (PAM)

**English:** PAM is a security practice and solution to control, monitor, and secure accounts that have elevated (high-level) access to critical systems.

**Urdu:** PAM ek system hai jo un accounts ko secure karta hai jo admin ya superuser level ka access rakhte hain (ye accounts sabse zyada risky hote hain).

## Key Components of a PAM Solution

### Credential Vaulting

Store privileged account passwords in a secure vault.

**Urdu: Ye ek password vault hota hai jahan sensitive passwords encrypted form me store hote hain.**

### Session Management

Monitor and record admin sessions.

**Urdu:** Jab admin login karta hai aur kaam karta hai, system uski session ko record karta hai taake koi misuse na ho.

### Least Privilege Enforcement

Users only get required privileges, nothing extra.

**Urdu:** Sirf utna hi access milta hai jitna zarurat hai.

### Just-in-Time (JIT) Access

Temporary elevated access given when needed.

**Urdu:** Admin rights permanent nahi diye jate, sirf jab kaam ho tabhi diye jate hain.

### Auditing & Reporting

Logs of who accessed what and when.

**Urdu:** Har activity ka record aur audit trail maintain hota hai.

### Privileged Account
**English:** A privileged account is an account with higher access rights than normal users, often with the ability to modify systems, users, and configurations.

**Urdu:** Ye wo account hota hai jiske pass extra powers hoti hain, jaise system ko change karna ya users ko control karna.

## Examples of Privileged Accounts

Local Administrator Account → Windows admin account.

Domain Admin Account → Controls Active Directory and all connected systems.

Root Account → Linux/Unix superuser.

Service Accounts → Accounts used by apps/services with elevated rights.

Database Admin Account (DBA) → Full access to databases.

## Zero Standing Privilege (ZSP)

**English:** A security principle where no user has permanent privileged access. Instead, privileges are granted only when needed (JIT).

**Urdu:** Iska matlab hai ke kisi ke pass hamesha ka admin access nahi hota. Jab zarurat ho tabhi system temporary rights deta hai, aur kaam khatam hone ke baad wo rights khatam ho jate hain.

## Quick Summary Mix:

**PAM**= Protecting and managing high-risk accounts.

**Components** = Vaulting, session recording, least privilege, JIT access, auditing.

**Privileged Accounts** = Admin, Root, DBA, Service accounts.

**Zero Standing Privilege** = No permanent admin rights, only temporary when needed.

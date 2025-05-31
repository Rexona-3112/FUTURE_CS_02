## 🛠 Tools & Environment

| Component     | Details                             |
| ------------- | ----------------------------------- |
| OS            | Kali Linux                          |
| Tool          | Social Engineering Toolkit (SET)    |
| Target        | Local/test victim machine           |
| Attack Vector | Credential harvesting via web clone |
| Browser Used  | Firefox                             |
| IP Address    | Localhost IP of Kali machine        |

---

## 📋 Step-by-Step Methodology

### 🔹 Step 1: Launch SET

Open the terminal in Kali Linux:

```bash
setoolkit
```

This opens the SET interface.

---

### 🔹 Step 2: Select Social-Engineering Attacks

From the SET main menu:

```
1) Social-Engineering Attacks
```

---

### 🔹 Step 3: Choose Website Attack Vectors

Select:

```
2) Website Attack Vectors
```

---

### 🔹 Step 4: Choose Credential Harvester Attack Method

Next, choose:

```
3) Credential Harvester Attack Method
```

---

### 🔹 Step 5: Use Web Templates

Select:

```
1) Web Templates
```

Then:

* Enter your **Kali Linux IP address**.
* Select **Twitter** as the cloned template.

---

### 🔹 Step 6: Open Phishing Page in Firefox

On the victim system:

* Launch Firefox.
* Enter the Kali IP address in the address bar.
* A **Twitter login clone** will appear.

---

### 🔹 Step 7: Enter Dummy Credentials

Type in:

* Any test **username** and **password**.

These will be captured by the SET backend.

---

### 🔹 Step 8: Check Captured Credentials

Return to the SET terminal on Kali:

* View the logged credentials in plain text.

---

## 📊 Findings

* ✅ **Website Clone Accuracy**: The Twitter page appeared authentic.
* 🛑 **Credential Logging**: Dummy credentials were captured successfully.
* ⚠️ **No Alerts**: The phishing site wasn’t blocked by browser or filters during simulation.

---

## 📉 Analysis

* **User Behavior Risk**: Users can easily fall for familiar-looking websites.
* **Ease of Use**: SET simplifies phishing attack creation.
* **Lack of Defense**: Without tools like MFA, web filtering, or antivirus, systems are exposed.

---

## 🛡 Recommendations

* 📚 **Security Awareness**: Regular training and phishing simulations.
* ✉️ **Email Filtering**: Use spam filters and sandboxing to catch threats.
* 🧩 **Browser Security**: Install browser extensions to flag phishing sites.
* 🔐 **Enable MFA**: Reduce damage from compromised credentials.
* 🧪 **Routine Testing**: Conduct periodic phishing tests on staff.

---

## ✅ Conclusion

This phishing simulation using the Social Engineering Toolkit successfully demonstrated how attackers exploit **human trust** and **technical gaps**. It reinforces the need for:

* **Layered defenses**
* **Employee vigilance**
* **Proactive monitoring**

---

**Prepared by:** Shayan Chakraborty
**Date:** 31-05-2025

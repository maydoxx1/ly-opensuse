# ly-opensuse

> 🎉 An **unofficial openSUSE RPM port** of the legendary TUI login manager [ly](https://github.com/fairyglade/ly)  
> ✨ Minimal, beautiful, and now installable with just `zypper`.

---

## 📦 What is This?

This is a native `.rpm` package of `ly`, the text-based (TUI) login manager, built specifically for **openSUSE** systems.  
The original project is no longer actively maintained, so I took matters into my own hands.

---

## 🔥 Features

- Fast and lightweight login UI (TTY-based)
- Perfect for **minimal setups**
- Built for **openSUSE Tumbleweed / Leap**
- 🧠 Your brain will get stronger figuring out PAM 🫠

---

## 📥 Download

Grab the latest `.rpm` from the [**Releases**](https://github.com/maydoxx1/ly-opensuse/releases/latest) page:

- ✅ [`ly-0.5-1.x86_64.rpm`](https://github.com/maydoxx1/ly-opensuse/releases/download/v1.0/ly-0.5-1.x86_64.rpm)  
  SHA256: `34c3d7e77ed919fe1e0404f1dbbc164f978425a1a475fea9f57851a967d61c14`

---

## 🚀 Installation (Tumbleweed / Leap)

```bash
wget https://github.com/maydoxx1/ly-opensuse/releases/download/v1.0/ly-0.5-1.x86_64.rpm
sudo zypper install ./ly-0.5-1.x86_64.rpm
sudo systemctl enable ly.service
sudo systemctl set-default multi-user.target
reboot
```

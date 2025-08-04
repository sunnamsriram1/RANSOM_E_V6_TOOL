# RANSOM_E_V6_TOOL


# 🔐 RANSOM_E_V6_TOOL (ఫైల్ లాకర్ & డీక్రిప్టర్)

> ఒక శక్తివంతమైన Python టూల్ — గోప్యంగా ఫోల్డర్‌లను లాక్ (ఎన్‌క్రిప్ట్) చేయడానికి మరియు డీక్రిప్ట్ చేయడానికి.  
> ఫైల్ పేర్లు కూడా హైడెడ్ మోడ్‌లో **AES (Fernet)** ద్వారా సురక్షితంగా జమ చేయబడతాయి.  
> ⚠️ తప్పు పాస్‌వర్డ్ 3సార్లు ఇస్తే **ఫైళ్ళు స్వతహాగా delete అవుతాయి** (Self-destruct)!

---

## 🧰 లక్షణాలు (Features):

✅ **AES (Fernet)** ఆధారిత military-grade encryption  
✅ ఫైల్ పేరు, కంటెంట్ రెండూ గోప్యంగా మారుతుంది  
✅ **Auto-generated strong password** ఫీచర్  
✅ **Password Hint** సేవ్ చేయగలిగే విధంగా  
✅ **Self-Destruct** మెకానిజం (3 wrong tries = delete)  
✅ **Multithreading** ద్వారా ultra-fast locking/unlocking  
✅ **Manifest file (`manifest.locked`)** లో గోప్యంగా అన్ని ఫైళ్ళు లాగింగ్  
✅ Clipboard లో పాస్‌వర్డ్ copy ఫీచర్  
✅ రంగులతో (color-based alerts) CLI user-interface  
✅ Backup folder name మరియు info auto-create అవుతుంది  
✅ **Termux**, Linux, Windows (Python-supported) platforms‌లో పని చేస్తుంది

---

## ⚙️ అవసరమైన Python ప్యాకేజీలు

```bash
pip install cryptography pyperclip
bash Ransome_eE_4v_3V.py
```
## అప్పుడు స్క్రిప్ట్ అడుగుతుంది:

- 📁 ఫోల్డర్ పాత్ ఇవ్వండి (లాక్ చేయాల్సినది)

- 🔄 మోడ్ ఎంచుకోండి: lock లేదా unlock

- 🔐 Auto password తీసుకోవాలా? (y/n)

- Yes: random strong password చూపుతుంది, clipboard లో కూడా సేవ్ అవుతుంది.

- No: మానవంగా మీ password ఇవ్వండి.

- ✅ హింట్ ఇచ్చి future లో గుర్తు పెట్టుకోండి.

- 🔒 Encrypt చేస్తుంది అన్ని ఫైళ్ళను.

- ✅ manifest.locked, salt.locked, .locked files create అవుతాయి.

- 🔓 Unlock చేసేటప్పుడు సరైన password ఇస్తే రికవరీ అవుతుంది.

## ⚠️ జాగ్రత్తలు
- పాస్‌వర్డ్ మర్చిపోతే, డేటా తిరిగి పొందలేరు!

- 3 సార్లు తప్పుగా పాస్‌వర్డ్ ఇస్తే, స్క్రిప్ట్ ఫైళ్ళను delete చేస్తుంది!

- తప్పనిసరిగా hint.txt సేవ్ చేయండి లేదా manifest.locked బయటకి బ్యాకప్ చేయండి.

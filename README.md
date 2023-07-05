```bash
#!/bin/bash
db_set() {
  echo "$1,$2" >> database
}

db_get() {
  grep "^$1," database | sed -e "s/^$1,//" | tail -n 1
}
```

  ![MedivhGO's github stats](https://github-readme-stats.vercel.app/api?username=MedivhGO&count_private=true&show_icons=true&hide_border=true)

- 👀 I’m interested in Database System
- 🌱 I’m currently learning DB OS ARCH CPP
- 📫 How to reach me lijingqi93@outlook.com

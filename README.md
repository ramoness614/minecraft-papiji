# Minecraft Bossfight Mods

Game voxel 3D bergaya Minecraft dalam satu file HTML (Three.js).
Fitur: dunia acak 5 pulau bertema (utama, salju, kota kuno, jamur, End),
portal antar pulau, 37 boss di darat, laut & langit, pistol, mode terbang,
simpan progres otomatis, kontrol PC + mobile.

Dua mode di menu: **MAIN** (boss muncul satu per satu) dan **ALL BOSS**
(seluruh boss muncul bersamaan).

## Boss bermekanik khusus

| Boss | Mekanik |
|---|---|
| Lebah Penyengat | sengatannya meracuni; racun terus menggerogoti sampai lebahnya dikalahkan |
| Raja Nyamuk | menyedot darah selama menempel — HP terkuras, boss ikut pulih |
| Tangan Pencengkeram | menggenggam pemain, gerak terkunci & luka terus selama 4 detik |
| Lubang Hitam | mengisap pemain ke arahnya dan menahan 45% damage tembakan |
| Mata Besar | laser tak terlihat; hanya terhalang blok padat |
| Kaki Raksasa | melompat ke atas pemain lalu menghantam area |
| Venom | bertengger di pohon Pulau Jamur, melompat antar pohon |
| Boss laut | mati sendiri jika terdampar di darat |

## Deploy ke InsForge (Sites)

Dari folder ini, jalankan:

    npx @insforge/cli login
    npx @insforge/cli deployments deploy .

Setelah selesai, game bisa diakses di https://<appkey>.insforge.site

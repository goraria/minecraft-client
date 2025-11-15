# Minecraft Client

Repository chứa cấu hình và phiên bản Minecraft client.

## 📦 Nội dung

Repository này chứa:
- **Modpack** - Modpack

## 🚀 Cài đặt

1. Clone repository:
   ```bash
   git clone https://github.com/goraria/minecraft-client Minecraft
   ```

2. Di chuyển vào thư mục:
   ```bash
   cd Minecraft
   ```

3. Sử dụng launcher Minecraft Tải về **Industrial Pack 1.2** vào thư mục `versions/`.
    ```bash
   cd versions
   ```

4. Clone Modpack:
   ```bash
   git clone https://github.com/goraria/minecraft-modpack Cipher
   ```

## 📁 Cấu trúc thư mục

```
Minecraft/
├── assets/                      # Tài nguyên game (textures, sounds, models)
│   ├── indexes/                 # Index files cho assets
│   ├── log_configs/             # Cấu hình logging
│   ├── objects/                 # Asset objects (textures, sounds)
│   └── skins/                   # Player skins
├── backup/                      # Thư mục backup
├── config/                      # File cấu hình modpack
├── debug/                       # File debug và crash reports
├── downloads/                   # File đã tải về
├── libraries/                   # Java libraries và dependencies
│   ├── com/                     # Common libraries
│   ├── net/                     # Network libraries
│   ├── org/                     # Organization libraries
│   └── ...
├── logs/                        # Log files từ game sessions
├── mods/                        # Mod files (nếu có)
├── resourcepacks/               # Resource packs
├── runtime/                     # Java runtime files
│   ├── java-runtime-delta/
│   └── java-runtime-gamma/
├── saves/                       # World saves
├── saves-current/               # Current world saves
├── saves-new/                   # New world saves
├── server-resource-packs/       # Server resource packs
├── shaderpacks/                 # Shader packs
├── versions/                    # Minecraft versions và modpacks
│   ├── Industrial Pack 1.2/     # Core
│   └── Modpack/                 # Modpack
├── tlLoader/                    # TLauncher loader files
├── .gitignore                   # Cấu hình Git ignore
├── .gitattributes               # Git attributes
├── README.md                    # File README này
├── command_history.txt          # Lịch sử lệnh
├── launcher_profiles.json       # Cấu hình launcher profiles
├── options.txt                  # Game options
├── optionsof.txt                # OptiFine options
├── optionsshaders.txt           # Shader options
├── servers.dat                  # Server list
├── TlauncherProfiles.json       # TLauncher profiles
├── TempOptifineStore-1.0.json   # OptiFine temp store
├── usercache.json               # User cache
└── worlds.json                  # Worlds configuration
```

## 📝 Lưu ý

- Repository này chỉ chứa phiên bản **Industrial Pack 1.2** core dành cho Modpack
- Các file khác (logs, mods, saves, resourcepacks, v.v.) đã được ignore và không được commit vào repository
- Để sử dụng Modpack, bạn cần có Minecraft launcher hỗ trợ custom versions

## 🔧 Yêu cầu

- Minecraft Launcher (TLauncher, MultiMC, hoặc tương tự)
- Java LTS 17 or 21 (Recommend using microsft-openjdk, oracle-jdk, openjdk)

## 📄 License

Xem file LICENSE để biết thêm chi tiết.

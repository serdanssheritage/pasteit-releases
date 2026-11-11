# PasteIT

Clipboard manager за Mac: история на копираното, workspaces, Private, скрийншоти с анотации и **Save to PasteIT** (десен клик върху снимка или видео и го пазиш за по-късно).

## ⬇️ Изтегляне

**[Изтегли последната версия (PasteIT.dmg)](https://github.com/serdanssheritage/pasteit-releases/releases/latest)** → в секцията **Assets** натисни `PasteIT-<версия>.dmg`.

Изисква macOS 14 или по-нов.

## Инсталиране

1. Отвори DMG-то и плъзни **PasteIT** в **Applications**.
2. Отвори PasteIT. macOS ще каже, че не може да провери приложението (не е минало през платената проверка на Apple) – натисни **Done**.
3. **System Settings → Privacy & Security** → най-долу при PasteIT натисни **Open Anyway** и потвърди.

   Или с една команда в Terminal:

   ```bash
   xattr -dr com.apple.quarantine /Applications/PasteIT.app
   ```

4. Разреши **Accessibility** (за директно поставяне), когато PasteIT поиска.

Отваряне: **⌘⇧P**. Новите версии идват автоматично (Settings → General → Updates).

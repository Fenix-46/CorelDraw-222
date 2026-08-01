# MyCorelDocker - CorelDRAW C# WPF Docker Add-In

Bu proyekt CorelDRAW üçün C# WPF əsasında hazırlanmış daxili panel (Docker) Add-In plaginidir. Panel istifadəçilərə `.cdr`, `.eps`, `.ai`, `.png`, `.jpg` fayllarını idarə etmək və Drag & Drop vasitəsilə sənədə daxil/ixrac etmək imkanı verir.

---

## 🚀 Xüsusiyyətlər
- 📁 **İmport**: Xarici faylları yerli `%AppData%/MyCorelLibrary/` kitabxanasına əlavə edir.
- 🎯 **Səhifədən Panelə (Drag & Drop)**: CorelDRAW sənədində seçilmiş obyekti sürüşdürüb panelin Drop sahəsinə atdıqda obyekt avtomatik kitabxanada `.cdr` olaraq saxlanılır.
- 🖼️ **Paneldən Səhifəyə (Drag & Drop)**: Paneldəki elementi tutub sənədin üzərinə atdıqda avtomatik CorelDRAW səhifəsinə import olunur.

---

## 🛠️ Quraşdırma (Installation)

1. Proyekti GitHub Actions vasitəsilə və ya Visual Studio-da `x64 Release` rejimində compile edin.
2. Yaradılan `MyCorelDocker.dll` və `AppUI.xml` fayllarını aşağıdakı qovluğa kopyalayın:
   ```text
   C:\Program Files\Corel\CorelDRAW Graphics Suite 202X\Draw\Plugins64\MyCorelDocker\
   ```
3. CorelDRAW proqramını başladın.
4. Yuxarı menyudan **Window -> Dockers -> My Corel Library** panelini aktivləşdirin.

<p align="center">
  <img src="https://github.com/MronRunned/Terraform-New-Dawn/raw/a6ca68dca2b114d46ffcba7514d8cc02ec8a5bb9/banner.webp" alt="Terraform: New Dawn Banner" width="500" style="border-radius: 20px;"/>
</p>

<h1 align="center">🌱 Terraform: New Dawn</h1>
<h3 align="center">Where Barren Worlds Bloom and Legends Are Forged</h3>

<p align="center">
  <img src="https://img.shields.io/badge/Version-0.1.0%20Alpha-ff6b35?style=for-the-badge&logo=starship&logoColor=white"/>
  <img src="https://img.shields.io/badge/C++-17-00599C?style=for-the-badge&logo=cplusplus&logoColor=white"/>
  <img src="https://img.shields.io/badge/SFML-2.5.0-8CC84B?style=for-the-badge&logo=sfml&logoColor=white"/>
</p>

<p align="center">
  <em>In the silent echoes of a dead world, one pioneer's courage will awaken a new dawn.</em>
</p>

---

## ✨ Embark on the Ultimate Terraforming Journey

**Terraform: New Dawn** is an immersive 2D survival-sandbox experience where you become the architect of life on a forgotten planet. From the first lonely sunrise to the thriving ecosystem you'll cultivate, every moment tells a story of resilience and creation.

# Clone using this URL
## https://github.com/MronRunned/Terraform-New-Dawn.git

```cpp
// Your journey begins here
World::create("New Horizon");
Player::becomePioneer();
Dawn::await();
```

## 🎮 Visual Evolution: Before vs After

<div style="position: relative; width: 100%; height: 0; padding-bottom: 56.25%; margin: 20px 0;">
  <input type="radio" name="slider" id="before" checked style="display: none;">
  <input type="radio" name="slider" id="after" style="display: none;">
  
  <div style="position: absolute; width: 100%; height: 100%;">
    <label for="before" style="position: absolute; left: 10px; top: 10px; background: #ff4444; color: white; padding: 8px 16px; border-radius: 20px; cursor: pointer; z-index: 100;">Before</label>
    <label for="after" style="position: absolute; right: 10px; top: 10px; background: #4CAF50; color: white; padding: 8px 16px; border-radius: 20px; cursor: pointer; z-index: 100;">After</label>
  </div>

  <div style="position: absolute; width: 100%; height: 100%; overflow: hidden; border-radius: 15px; box-shadow: 0 8px 32px rgba(0,0,0,0.3);">
    <!-- BEFORE -->
    <div style="position: absolute; width: 100%; height: 100%; transition: opacity 0.3s ease; opacity: 1;" id="before-content">
      <img src="https://via.placeholder.com/800x450/ff4444/ffffff?text=Basic+Prototype+Before" style="width: 100%; height: 100%; object-fit: cover;">
      <div style="position: absolute; bottom: 0; left: 0; right: 0; background: linear-gradient(transparent, rgba(0,0,0,0.8)); color: white; padding: 20px;">
        <h3 style="margin: 0; color: #ff6b6b;">Basic Prototype</h3>
        <p style="margin: 5px 0 0 0;">Simple graphics, placeholder UI, no visual effects</p>
      </div>
    </div>

    <!-- AFTER -->
    <div style="position: absolute; width: 100%; height: 100%; transition: opacity 0.3s ease; opacity: 0;" id="after-content">
      <img src="https://via.placeholder.com/800x450/4CAF50/ffffff?text=Enhanced+Experience+After" style="width: 100%; height: 100%; object-fit: cover;">
      <div style="position: absolute; bottom: 0; left: 0; right: 0; background: linear-gradient(transparent, rgba(0,0,0,0.8)); color: white; padding: 20px;">
        <h3 style="margin: 0; color: #51cf66;">Enhanced Experience</h3>
        <p style="margin: 5px 0 0 0;">Dynamic lighting, particle effects, animated UI</p>
      </div>
    </div>
  </div>
</div>

<script>
document.addEventListener('DOMContentLoaded', function() {
  const before = document.getElementById('before');
  const after = document.getElementById('after');
  const beforeContent = document.getElementById('before-content');
  const afterContent = document.getElementById('after-content');

  before.addEventListener('change', function() {
    beforeContent.style.opacity = '1';
    afterContent.style.opacity = '0';
  });

  after.addEventListener('change', function() {
    beforeContent.style.opacity = '0';
    afterContent.style.opacity = '1';
  });
});
</script>

## 📊 Что было улучшено:

### 🎨 Визуальные улучшения:
- **Динамическое освещение** - реалистичные тени и свет
- **Система частиц** - дым, огонь, погодные эффекты  
- **Анимированный UI** - плавные переходы и hover-эффекты
- **Погодная система** - дождь, снег, бури с визуальным impact

### 🎮 Геймплейные механики:
- **Продвинутое строительство** - rotation, snapping, multi-block
- **Электрическая сеть** - визуализация потоков энергии
- **Динамика жидкостей** - реалистичное течение воды/лавы
- **Экосистема** - рост растений, поведение существ

### ⚙️ Технические улучшения:
- **OpenGL рендеринг** - аппаратное ускорение
- **GLSL шейдеры** - 8+ визуальных эффектов
- **Система анимаций** - bone-based анимация
- **Оптимизация** - 60 FPS даже на слабых ПК

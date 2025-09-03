# ESO Light Weaving Script

A comprehensive Cronus Zen script for **Elder Scrolls Online** that automates light attack weaving and animation cancelling for optimal DPS performance.

## 🎯 Features

### **Core Functionality**
- **Light Attack Weaving**: Automatic light attack → skill → block cancel sequences
- **Animation Cancelling**: Precise timing for ESO's combat mechanics
- **Ultimate Combos**: Automated ultimate → skill combinations
- **Per-Button Control**: Individual settings for each skill button
- **ESO-Optimized Timing**: Based on ESO's 1000ms GCD and animation frames

### **Advanced Options**
- **Individual LA Toggle**: Enable/disable light attacks per button
- **Block Cancelling**: Configurable block cancel for each skill
- **Ultimate Modes**: Auto-combo or manual ultimate handling
- **Responsive Detection**: Smooth button detection with pressure thresholds
- **Settings Persistence**: Automatic save/load of all configurations

### **Display & Interface**
- **OLED Menu System**: Full settings menu with L2+Options
- **Animated Startup**: "ESO - WEAVING" logo with character-by-character animation
- **LED Indicators**: Color-coded status lights (Yellow=active, Green=enabled, Red=disabled)
- **Save Confirmation**: "SETTINGS WAS SAVED" message on menu exit

## 🎮 Controls

### **Menu Navigation**
- **L2 + Options**: Open settings menu
- **D-Pad Up/Down**: Navigate menu items
- **D-Pad Left/Right**: Adjust values/toggle options
- **Circle**: Save settings and exit menu

### **Skill Buttons**
- **Square**
- **Triangle**
- **Circle**
- **L1**
- **R1**
- **L1 + R1**

## ⚙️ Menu Settings

### **Global Settings**
| Setting | Description | Range | Default |
|---------|-------------|-------|---------|
| Weaving | Master toggle for all weaving | ON/OFF | ON |
| R2 Hold Time | Light attack duration | 30-400ms | 80ms |
| Gap Before Skill | Delay after LA, before skill | 50-400ms | 100ms |
| Gap Before Block | Delay after skill, before block | 50-400ms | 180ms |
| L2 Hold Time | Block cancel duration | 30-400ms | 350ms |

### **Per-Button Settings** (Square/Triangle/Circle/L1/R1)
| Setting | Description | Options |
|---------|-------------|---------|
| [Button] LA | Light attack for this button | ON/OFF |
| [Button] Skill Hold | How long to hold the skill button | 0-400ms |
| [Button] Block | Block cancel for this button | ON/OFF |

### **Ultimate Settings**
| Setting | Description | Options |
|---------|-------------|---------|
| Ult Combo Mode | Automatic ultimate combos | ON/OFF |
| Ultimate Hold | L1+R1 hold duration | 0-500ms |
| Ult Skill Button | Which skill to use after ultimate | R1/L1/Square/Circle/Triangle |
| Ult Skill Hold | Skill hold time after ultimate | 10-400ms |

## 🚀 Installation

1. **Load Script**: Import `eso_light_weaving.gpc` into Cronus Zen software
2. **Compile**: Build the script (32-bit)
3. **Upload**: Transfer to your Cronus Zen device
4. **Configure**: Open menu with L2+Options and adjust settings

## 💡 Usage Tips

### **For Beginners**
- Start with default settings - they're optimized for most situations
- Enable weaving and try it on a training dummy first
- Adjust timing values gradually if you experience lag

### **For Advanced Users**
- **Disable LA on specific buttons** for buffs/heals
- **Disable block cancel** for channeled skills
- **Tune hold times** based on your skill animations
- **Ultimate combos** work great for burst rotations

### **ESO-Specific Tips**
- **Spammables**: Enable LA + Block for max DPS
- **Channeled Skills**: Enable LA, disable Block
- **DOTs**: Enable LA, disable Block to avoid interruption
- **Buffs/Heals**: Disable LA, enable Block for quick casting

## 🔧 Timing Optimization

### **Low Latency** (0-50ms ping)
- Use default settings
- Consider reducing gaps slightly (90ms skill gap, 160ms block gap)

### **Medium Latency** (50-100ms ping)
- Increase Gap Before Skill to 120-140ms
- Increase Gap Before Block to 200-220ms

### **High Latency** (100ms+ ping)
- Increase Gap Before Skill to 150ms+
- Increase Gap Before Block to 250ms+
- Consider increasing R2 Hold Time to 100ms

## 📊 LED Status Indicators

| Color | Meaning |
|-------|---------|
| **Yellow** | Script active, basic mode |
| **Green** | Weaving enabled and active |
| **Red** | Weaving disabled |
| **Blue** | Ultimate combo active |

## 🛠️ Troubleshooting

### **Common Issues**

**Weaving not working:**
- Check that Weaving is ON in menu
- Verify button LA toggles are enabled
- Ensure you're holding buttons long enough

**Skills interrupting:**
- Increase Gap Before Skill
- Disable block cancel for channeled abilities
- Check skill hold times

**Lag/delay issues:**
- Increase all gap timings
- Check your internet connection
- Consider latency compensation

**Ultimate not firing:**
- Enable Ult Combo Mode
- Check Ultimate Hold time
- Verify L1+R1 button detection

### **Performance Tips**
- **Don't spam buttons** - press and hold for best results
- **Practice rotation timing** on training dummies first
- **Adjust gradually** - small changes (10-20ms) work best

## 📋 Version Information

- **Version**: Enhanced v2.0
- **Game**: Elder Scrolls Online
- **Device**: Cronus Zen
- **Language**: GPC Script
- **Menu Items**: 24 configurable settings

## 🔄 Updates & Changes

### **v2.0 Features**
- ✅ Simplified save system
- ✅ Enhanced startup display with ESO branding
- ✅ Improved button detection and responsiveness
- ✅ Per-button light attack and block control
- ✅ Ultimate combo system with button selection
- ✅ LED status indicators
- ✅ Settings persistence across sessions

---

**Happy Weaving, and may your DPS be ever high! ⚔️**

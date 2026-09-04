# 黄额闭壳龟饲养环境 — Midjourney 图片生成提示词

---

## 提示词（英文）

```
A photorealistic interior view of a terrestrial turtle vivarium housing a Cuora galbinifrons (Vietnamese box turtle), top-down 3/4 angle perspective.

Enclosure: A large glass terrarium, approximately 90×60×45cm, with a wooden frame top partially open. The enclosure is divided into distinct zones.

Substrate layer: A deep (8cm) mixed substrate of dark coconut coir, shredded sphagnum moss, and dried oak leaves scattered across the floor, creating a naturalistic forest floor appearance. The substrate appears slightly moist with visible texture variation.

Vegetation and decor: Several pieces of driftwood and cork bark arranged to form climbing structures and hiding spots. Two cork bark hide boxes tucked into corners — one in the warm zone, one in the cool zone. Live pothos plants and a small fern growing from the back wall. Dried magnolia leaves scattered on the substrate surface.

Water area: A shallow ceramic water dish sunk into the substrate on one side, filled with clean water at a depth of 2cm, large enough for the turtle to soak but with a gentle ramp for easy entry and exit.

Lighting: A dome ceramic heat emitter mounted on one end of the top mesh lid casting warm light downward, creating a visible basking zone. A linear fluorescent UVB tube runs along the opposite side of the lid. Soft warm ambient lighting fills the enclosure.

Climate equipment: A small digital hygrometer-thermometer probe clipped to the side wall, display showing 27°C and 78% humidity. Fine mist droplets visible on the glass walls from recent spraying.

The turtle: One adult Cuora galbinifrons with a high-domed carapace featuring distinctive yellow and black patterning on each scute, walking through the leaf litter near the center of the enclosure, head extended forward in a natural foraging posture.

Atmosphere: Warm, humid, lush. Condensation on the upper glass panels. The overall impression is a dense tropical montane forest floor microhabitat captured in a home terrarium setting.

Photography style: Natural indoor lighting mixed with the warm glow of the heat lamp, shallow depth of field focused on the turtle, soft shadows, shot on a Canon EOS R5 with a 35mm lens, f/2.8, editorial wildlife photography style.

--ar 4:3 --v 6.1 --style raw --s 200
```

---

## 提示词结构拆解

| 段落 | 描述内容 | 视觉作用 |
|------|----------|----------|
| Enclosure | 玻璃饲养箱尺寸与视角 | 确定画面框架与透视 |
| Substrate | 椰土+水苔+落叶混合底材 | 营造森林地表质感 |
| Vegetation | 沉木、树皮躲避、绿植、落叶 | 构建空间层次与遮蔽 |
| Water area | 浅水盆+斜坡 | 体现水域功能区 |
| Lighting | 陶瓷加热灯+UVB灯管 | 展示设备与光照氛围 |
| Climate | 温湿度计+玻璃水雾 | 传达高湿环境信息 |
| The turtle | 成体黄额闭壳龟外观与姿态 | 主体物种特征 |
| Atmosphere | 温暖、湿润、凝结水珠 | 整体环境氛围 |
| Photography | 相机参数与拍摄风格 | 控制画面质感 |

---

## 可选变体

### 变体 A：侧重环境全景（不含龟）

在提示词末尾将 `The turtle` 段落替换为：

```
No turtle visible. The enclosure appears ready for habitation, with a natural foraging path worn through the leaf litter leading from one hide to the water dish.
```

追加参数：`--no turtle, animal, creature`

### 变体 B：夜间模式

替换 Lighting 段落为：

```
Nighttime setting. A low-wattage red ceramic heat emitter provides dim red glow as the only light source. The enclosure is mostly in shadow. The UVB lamp is off. Moonlight simulation through the mesh lid casts faint cool-blue highlights on the glass walls.
```

### 变体 C：幼体饲养箱（更小尺度）

替换 Enclosure 段落为：

```
A compact plastic tub enclosure approximately 45×30×25cm with ventilation holes drilled into the sides and lid, viewed from above at a 45-degree angle. Inside is a juvenile Cuora galbinifrons hatchling, carapace length approximately 5cm.
```

---

## 使用建议

- **比例**：`--ar 4:3` 适合展示饲养箱全貌；如需横版宽幅可改为 `--ar 16:9`
- **风格化程度**：`--s 200` 保持较低风格化以维持写实感；提高至 `--s 500` 可获得更具艺术感的画面
- **版本**：`--v 6.1` 为当前写实能力最强的版本
- **负面提示**：如出现不想要的元素，追加 `--no cartoon, illustration, diagram, text, watermark`

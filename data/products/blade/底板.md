---
id: butterfly-viscaria
brand_id: butterfly            # 必須對應 data/brands/ 中的 id
category: blade
series: Viscaria               # 所屬產品系列（如 Innerforce, Timo Boll, Hurricane Long）
name_en: Viscaria
name_zh: 維斯卡利亞
aliases: ["蝴蝶王", "VIS", "30041"] # 台灣/華語圈常見俗稱與官方型號
release_year: 1993
status: active                 # active (現售) | discontinued (已停產)

specs:
  playstyle: OFF               # DEF | ALL | ALL+ | OFF- | OFF | OFF+
  structure_type: outer-fiber  # all-wood | outer-fiber | inner-fiber | single-hinoki
  plies_count: 7               # 總層數（如 5, 7, 1）
  composition: "5木 + 2 ALC (外置)"
  wood_layers:                 # 已知則填寫，未知填 null
    surface: Koto (寇頭)
    fiber: Arylate-Carbon (芳碳纖維)
    medial: Limba (林巴)
    core: Kiri (桐木)
  thickness_mm: 5.8            # 官方公稱板身厚度 (mm)
  head_size_mm:
    length: 157
    width: 150
  handle_types:                # 支援的握柄規格與尺寸
    - code: FL                 # FL | ST | AN | CS | JP
      length_mm: 100
      thickness_mm: 25
      width_end_mm: 34
    - code: ST
      length_mm: 100
      thickness_mm: 23
      width_end_mm: 28
  weight_avg_g: 87             # 官方平均重量 (g)，若官方未公佈填 null
  made_in: Japan
  jtta_approved: true          # 是否具備 JTTA 認證
---

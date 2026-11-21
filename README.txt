ANGEL LAB - ALL CHARACTER FOUNDATION (NEW NETLIFY SITE)

This is a new-site deployment package, not a patch-only update.
Upload the contents of this ZIP to a NEW Netlify site.

Game and character selection:
- Separate GAME and CHARACTER selectors.
- KOF XV character catalog (61 entries).
- Fatal Fury: City of the Wolves character catalog (35 entries, including announced/upcoming entries).
- Populated CotW move lists: Rock Howard, Terry Bogard, B. Jenet, Marco Rodrigues, Preecha, Hotaru Futaba, Vox Reaper, Griffon Mask, Kevin Ryan, Billy Kane, Shiranui Mai, Kim Dong Hwan, Gato (牙刀／ガトウ), Cain R. Heinlein, Hokutomaru, Andy Bogard, Rick Stroud, Duck King, Kenshiro, Kim Kaphwan, Mikey, Draken, and Laocorn.
- Angel and Rick profiles retain their existing move data, combos, and notes.
- Mr.カラテ: 54 selectable entries (normal moves, throws, command combos, special moves, stance follow-ups, REV Blows, supers, Hidden Gear). Phase 28 R1 embeds the audited Mr.カラテ profile initialization directly in index.html.
- Duck King: 53 selectable entries after Phase 29 R1 audit: 52 character entries plus the shared step action (normal attacks, throws, step/backstep actions, normal/REV special moves, Beat Rush branches, REV Blows, supers, Hidden Gear, and shared systems). Command notation normalized to LP/LK/HP/HK; Beat Rush branch conditions that remain unverified are explicitly noted.
- Other character profiles remain selectable placeholders and will be filled in stages.

CotW move data in this build:
- Rock Howard: 56 selectable entries (normal moves, command combos, special moves, REV Arts, REV Blows, supers, potential supers, Hidden Gear, and shared system actions).
- Terry Bogard: 47 selectable entries (normal moves, command combos, weak/strong special moves, REV Arts, REV Blows, supers, potential supers, Hidden Gear, and shared system actions).
- B. Jenet: 58 selectable entries (normal moves, throws, command combo, combination attack routes, special moves and follow-ups, REV Arts, REV Blows, supers, potential supers, Hidden Gear, and shared system actions).
- Marco Rodrigues: 58 selectable entries (normal moves, throws, dodge attacks, combination routes, special moves, REV Arts, REV Blows, supers, potential supers, Hidden Gear, and shared system actions).
- Preecha: 56 selectable entries (normal moves, throws, command combos, combination attacks, special moves and follow-ups, REV Arts, REV Blows, supers, potential supers, Hidden Gear, and shared system actions).
- Hotaru Futaba: 57 selectable entries (normal moves, throws, command combos, combination attacks, special moves, REV Arts, REV Blows, supers, potential supers, Hidden Gear, and shared system actions).
- Vox Reaper: 49 selectable entries (normal moves, throws, dodge attacks, combination attacks, weak/strong/REV special moves, REV Blows, supers, potential supers, Hidden Gear, and shared system actions).
- Griffon Mask: 59 selectable entries (normal moves, throws, dodge attacks, command combo, special moves, REV Arts, REV Blows, supers, potential supers, Hidden Gear, and shared system actions).
- Kevin Ryan: 57 selectable entries (normal moves, throws, dodge attacks, combination routes, special moves, REV Arts, REV Blows, supers, potential supers, Hidden Gear, and shared system actions).
- Shiranui Mai: 71 selectable entries (normal moves, throws, dodge attacks, combination routes, command combo and follow-ups, weak/strong/REV special moves, Musasabi movement and follow-ups, ground/air REV Blows, supers, potential supers, Hidden Gear, and shared system actions).
- Kim Dong Hwan: 56 selectable entries (normal moves, throws, dodge attacks, combination routes, command combos, ground/air special moves, REV Arts, REV Blows, supers, potential supers, Hidden Gear, and shared system actions).
- Gato (牙刀／ガトウ): 69 selectable entries (normal moves, throws, dodge attacks, combination routes, command combos, stance and special-move follow-ups, REV Arts, ground/air REV Blows, supers, potential supers, Hidden Gear, and shared system actions).
- Cain R. Heinlein: 50 selectable entries (normal moves, throws, dodge attacks, command combos, weak/strong/REV special moves, feints, braking, REV Blows, supers, potential supers, and Hidden Gear).
- Rick Stroud: existing user-approved data and Japanese category labels retained.
- Hokutomaru: 64 selectable entries (normal moves, throws, dodge attacks, combination attacks, special moves, REV Arts, REV Blows, normal/potential supers, Hidden Gear, feint, braking, and shared system action).
- Andy Bogard: 59 selectable entries (normal moves, throws, dodge attacks, command combos, special moves and follow-ups, REV Arts, REV Blows, supers, potential supers, Hidden Gear, feint, braking, and shared system actions).
- All implemented CotW characters include shared-system options: 「ステップ/ダッシュ」「バックステップ」「ノーマルジャンプ」「小ジャンプ」「ダッシュジャンプ」「前方投げ」「後方投げ」. Existing profiles receive only missing entries; saved combos and user notes are preserved.
- For characters covered by it, the official SNK Japanese Arcade Style command list is prioritized. For B. Jenet and Marco, character command tables are cross-checked against the Japanese CotW Wiki and AppMedia. Generic system inputs are checked against the official SNK Japanese battle manual. Unverified frame data is not added as fact.

Data protection:
- Existing localStorage key angelLab_core_v1 is retained for compatibility.
- Existing Angel and Rick profile IDs are unchanged.
- Existing saved combos and notes are not overwritten.
- Rock, Terry, B. Jenet, Marco, Preecha, Hotaru, Vox, Griffon Mask, Kevin, Billy, Mai, Kim Dong Hwan, Gato, and Cain profile initialization only seeds the move list when it is empty and preserves any existing combo array.
- JSON backup format v3 remains compatible.
- Back up data before switching sites. Local browser storage is scoped by origin/site; a NEW Netlify site will not automatically inherit the old site's localStorage. Export JSON from the old site and import it on the new site after launch.

Icon:
- The supplied Angel icon image is used for icon-192, icon-512, maskable-512, and apple-touch-icon.

Research references:
- SNK official Japanese Arcade Style command list PDF: https://www.snk-corp.co.jp/official/fatalfury-cotw/guide/img/command_sp_arcade_jp.pdf
- SNK official Japanese battle system manual: https://www.snk-corp.co.jp/webmanual/fatalfury-cotw/battle/?lang=ja-JP
- Japanese CotW Wiki, Rock Howard: https://w.atwiki.jp/cotw/pages/17.html
- Japanese CotW Wiki, Terry Bogard: https://w.atwiki.jp/cotw/pages/29.html
- Japanese CotW Wiki, B. Jenet: https://w.atwiki.jp/cotw/pages/51.html
- AppMedia, B. Jenet command and frame table: https://appmedia.jp/grcotw/78795392
- Japanese CotW Wiki, Marco Rodrigues: https://w.atwiki.jp/cotw/pages/41.html
- AppMedia, Marco Rodrigues command and frame table: https://appmedia.jp/grcotw/78811781
- AppMedia, Preecha command and frame table: https://appmedia.jp/grcotw/78795395
- AppMedia, Hotaru Futaba command and frame table: https://appmedia.jp/grcotw/78795398
- AppMedia, Hotaru Futaba strategy and combo guide: https://appmedia.jp/grcotw/78831140
- Japanese CotW Wiki, REV Blow system: https://w.atwiki.jp/cotw/pages/61.html
- Japanese CotW Wiki, REV Blow system: https://w.atwiki.jp/cotw/pages/61.html
- Japanese CotW Wiki, Andy Bogard: https://w.atwiki.jp/cotw/pages/42.html
- Famitsu, Andy Bogard move overview: https://www.famitsu.com/article/202505/41766

Roster references:
- KOF XV official SNK character page and SNK press release.
- FATAL FURY: City of the Wolves official SNK character page, official patch notes, and Japanese CotW Wiki.

プリチャ技表の照合先：AppMedia「プリチャのフレーム表・コマンド」（2025-04-18公開、2026-11-14閲覧）。弱／強／REV、派生入力、REVブロウ、超必殺技、潜在超必殺技、ヒドゥンギアの表記を参照。数値コマンドは右向き基準。

双葉ほたる技表の照合先：AppMedia「双葉ほたるのフレーム表・コマンド」（2025-04-18公開、2026-11-14閲覧）。通常技、投げ、コマンドコンボ、必殺技の弱／強／REV、REVブロウ、超必殺技、潜在超必殺技、ヒドゥンギアを参照。右向き基準のテンキー表記。共通システムのREVブロウ条件はSNK公式ガイドと日本語CotW Wikiを参照。

Vox Reaper references:
- Japanese CotW Wiki, Vox Reaper: https://w.atwiki.jp/cotw/pages/44.html
- AppMedia, Vox Reaper command and frame table: https://appmedia.jp/grcotw/78795401
- Japanese CotW Wiki, REV Blow system: https://w.atwiki.jp/cotw/pages/61.html

Griffon Mask references:
- Japanese CotW Wiki, Griffon Mask: https://w.atwiki.jp/cotw/pages/28.html
- AppMedia, Griffon Mask command and frame table: https://appmedia.jp/grcotw/78795404
- SNK official Japanese battle system manual: https://www.snk-corp.co.jp/webmanual/fatalfury-cotw/battle/?lang=ja-JP

Griffon Mask commands are represented in numeric keypad notation with the character facing right. Charge inputs, command throws, normal/potential supers, and ground/air REV Blows are separate selectable entries.

Kevin Ryan references:
- Japanese CotW Wiki, Kevin Ryan: https://w.atwiki.jp/cotw/pages/36.html
- AppMedia, Kevin Ryan command and frame table: https://appmedia.jp/grcotw/78816842
- AppMedia, Kevin Ryan strategy and combo guide: https://appmedia.jp/grcotw/78850736

Kevin commands are represented in numeric keypad notation with the character facing right. Creeper follow-ups, charge levels for Hell Rotor, normal/potential supers, and ground/air REV Blows are separate selectable entries.


Billy Kane references:
- Japanese CotW Wiki, Billy Kane: https://w.atwiki.jp/cotw/pages/52.html
- AppMedia, Billy Kane command and frame table: https://appmedia.jp/grcotw/78816875
- AppMedia, Billy Kane strategy and combo guide: https://appmedia.jp/grcotw/78834593

Billy commands are represented in numeric keypad notation with the character facing right. Normal/REV special moves, command follow-ups, ground/air REV Blows, normal/potential supers, and Hidden Gear are separate selectable entries.


Shiranui Mai references:
- Japanese CotW Wiki, Shiranui Mai: https://w.atwiki.jp/cotw/pages/45.html
- AppMedia, Shiranui Mai command and frame table: https://appmedia.jp/grcotw/78795407
- AppMedia, Shiranui Mai strategy and combo guide: https://appmedia.jp/grcotw/78851549

Mai commands use numeric keypad notation with the character facing right. Musasabi movement directions, follow-up attacks, normal/potential supers, and ground/air REV Blows are separate selectable entries.


Kim Dong Hwan research references:
- Japanese CotW Wiki: https://w.atwiki.jp/cotw/pages/34.html
- AppMedia command/frame table: https://appmedia.jp/grcotw/78821210

Gato (牙刀／ガトウ) research references:
- Japanese CotW Wiki, Gato: https://w.atwiki.jp/cotw/pages/49.html
- AppMedia, Gato command and frame table: https://appmedia.jp/grcotw/78816887
- AppMedia, Gato strategy and combo guide: https://appmedia.jp/grcotw/78843587

Gato commands are represented in numeric keypad notation with the character facing right. Nagi stance, Kuroga/Higa/Hakuga branches, Fuuga follow-ups, normal/potential supers, and ground/air REV Blows are separate selectable entries. The Japanese reading is ガトウ.


Cain R. Heinlein references:
- Japanese CotW Wiki, Cain R. Heinlein: https://w.atwiki.jp/cotw/pages/35.html
- AppMedia, Cain command and frame table: https://appmedia.jp/grcotw/78795410
- AppMedia, Cain strategy and combo guide: https://appmedia.jp/grcotw/78833042
- Official SNK Japanese character page: https://www.snk-corp.co.jp/official/fatalfury-cotw/characters/kain.php

Cain commands are represented in numeric keypad notation with the character facing right. Schwartz Flame, Panzer, Lanze, and Rondo have separate weak/strong/REV entries; Lanze charge input, feint/braking options, ground/air REV Blows, normal/potential supers, and Hidden Gear are separately selectable.

Cain move list: 50 selectable entries. Existing saved combo arrays are preserved; initial moves are seeded only for a missing profile or a profile with an empty move list.


Update 2026-11-14:
- Display name restored to 「グリフォンマスク（ティゾック）」 at user request. The internal profile ID cotw-tizoc is intentionally unchanged to preserve existing local data and saved combos. The internal profile ID cotw-tizoc is intentionally unchanged to preserve existing local data and saved combos.
- Added the shared-system 「ステップ」 entry to every populated CotW character profile. Existing profile move lists receive the entry only if it is missing; saved combos and notes are not replaced.


Hokutomaru references:
- AppMedia, Hokutomaru command and frame table: https://appmedia.jp/grcotw/78821243
- AppMedia, Hokutomaru strategy and combo guide: https://appmedia.jp/grcotw/78833735
- Japanese CotW Wiki, Hokutomaru: https://w.atwiki.jp/cotw/pages/2435.html
- Japanese CotW Wiki, REV Blow system (Hokutomaru follow-up): https://w.atwiki.jp/cotw/pages/61.html

Hokutomaru commands use numeric keypad notation with the character facing right. Normal/REV Shuriken variants, ground/air special moves, combination routes, ground/air REV Blows, normal/potential supers, Hidden Gear, feint, and braking are separate selectable entries. Existing combos are preserved; move data is seeded only when the profile is missing or empty.


Phase 17 追加内容（2026-11-14）
・クリスティアーノ・ロナウドの技データを追加（通常技、投げ、避け攻撃、コマンドコンボ、必殺技、REVアーツ、REVブロウ、超必殺技、潜在超必殺技、ヒドゥンギア、共通システム）。
・既存プロフィールの保存コンボ・メモを保持し、ロナウドの技データは未登録または空の場合のみ初期登録。
・PWAキャッシュをPhase 17へ更新。


【Phase 18 共通機能更新】
・コンボビルダーに「用途」（連続技／セットアップ）を追加。
・技表／コンボ作成に「テクニック」（空振り／フレーム消費／ディレイ）を追加。技をルートに追加した後、テクニックを選ぶと直前の技に括弧付きで付与されます。例：5LP（空振り）。
・テクニック情報はコンボの各ステップに保存され、編集・バックアップにも保持されます。
・プリチャのコンビネーションアタック（REV）の末尾を「HP+HK」に修正。既存プロフィールにも安全に反映します。
・既存の保存コンボ、メモ、プロフィールID、バックアップ形式は維持します。


Phase 19 (2026-11-15): サルヴァトーレ・ガナッチの技データを追加。既存プロフィールのmovesが未登録または空の場合のみ初期データを登録し、既存combosは保持します。Phase 18の全ゲーム共通コンボ用途・テクニック機能を継承。


【Phase 20 更新】
・餓狼伝説 CotW「ケン」を追加（通常技、特殊技、必殺技、派生技、超必殺技、潜在超必殺技、ヒドゥンギア、共通システム）。
・既存プロフィールの保存コンボ／メモは上書きせず、ケンの技データが未登録または空の場合のみ初期登録します。
・PWAキャッシュをPhase 20に更新しました。


Phase 21 (Joe Higashi)
- Added Joe Higashi move profile and enabled character selection.
- Preserved existing profile IDs and stored combo data.
- Initial move seed is applied only when Joe profile is missing or empty.
- Universal combo usage/technique fields from Phase 18 are retained.


Phase 22: 春麗の技データを追加。初期登録は空プロフィールのみを対象とし、既存コンボ・メモは保持します。


【Phase 23：Mr.BIG追加】
・Mr.BIGの技データを追加（通常技、投げ、特殊技、必殺技、派生、REVブロウ、超必殺技、潜在超必殺技、ヒドゥンギア、共通システム）。
・既存プロフィールID cotw-mr-big を使用。既存の保存コンボ・メモは初期化しない。技データが未登録または空の場合のみ初期データを登録。
・全ゲーム共通の用途／テクニック機能を含むPhase 22を継承。


Phase 24 (2026-11-15)
- キム・ジェイフンの技データを追加。
- 既存プロフィール・保存コンボ・メモは初期化せず、追加キャラクターの未登録／空データ時のみ初期登録。
- 共通コンボ機能と既存バックアップ互換性を維持。

Phase 25-27 updates (2026-11-15 to 2026-11-16)
- Added Nightmare Geese, Blue Mary, and Wolfgang Krauser profiles.
- Wolfgang Krauser has 37 selectable entries, including normal throws, avoid attacks, special moves, Knee Halberd follow-ups, REV Arts, ground/air REV Blows, normal/potential supers, Hidden Gear, and shared-system actions.
- Krauser's command table was audited on 2026-11-16. Verified commands were entered in numeric keypad notation for a right-facing character. The REV Art commands use the official manual's corresponding weak+strong button pair (P+P or K+K) with the same motion input.
- The following remain explicitly marked 「要確認」 rather than guessed: Command Combo ① (the wiki command is image-based and could not be transcribed with confidence) and the existence/input of a Knee Halberd Stab follow-up from the REV version (the wiki lists the REV follow-up as Lunge).
- A safe one-time data migration updates only Krauser move command fields that still match the original Phase 27 defaults. It does not alter any combo arrays, saved combo recipes, user-edited commands, notes, profile IDs, or the JSON backup schema.
- PWA cache version updated for the audited build.

Krauser command-audit references:
- Official SNK Japanese Web Manual, Battle System (REV Arts, REV Blow, Avoid Attacks, supers, Hidden Gear, throws): https://www.snk-corp.co.jp/webmanual/fatalfury-cotw/battle/?lang=ja-JP
- Japanese CotW Wiki, Wolfgang Krauser command table and move notes: https://w.atwiki.jp/cotw/pages/54.html
- Japanese CotW Wiki, Avoid Attack universal inputs: https://w.atwiki.jp/cotw/pages/64.html
- Japanese CotW Wiki, REV Blow universal input: https://w.atwiki.jp/cotw/pages/61.html
- Japanese CotW Wiki, Step/Dash character classification and inputs: https://w.atwiki.jp/cotw/pages/78.html
- Japanese CotW Wiki, Feint common input: https://w.atwiki.jp/cotw/pages/75.html
- Japanese CotW Wiki, Braking common input: https://w.atwiki.jp/cotw/pages/86.html
- Japanese CotW Wiki, Small Jump simplified input: https://w.atwiki.jp/cotw/pages/26.html
- Official SNK Japanese character page (character identity/background; not a command source): https://www.snk-corp.co.jp/official/fatalfury-cotw/characters/krauser.php

Krauser command notes:
- Normal special moves are listed with their weak/strong input separately.
- REV Arts are listed as the same motion input plus simultaneous weak+strong buttons of the corresponding attack type.
- Normal supers use weak buttons; Potential Supers use strong buttons. Hidden Gear requires S.P.G. and two power bars.
- REV Blow uses strong P+strong K during S.P.G.; the aerial version is performed in the air.
- Krauser is classified as a Step character; common input is ground 66 or 6+REV.
- Common-system entries are also transcribed: Feint = 強K+REV; Braking = during a BR-enabled special, REV or 弱P+弱K; Small Jump = quick 7/8/9 or REV+7/8/9.
- The command table's 4/6 follow-up notation for Knee Halberd Stab/Lunge is retained as 4/6; the REV Stab entry is not assumed to exist.

Data protection note for this audit:
- The Krauser migration only changes a command field when it exactly matches the old Phase 27 default value. If a user has manually edited that command, the edit is left untouched.
- Existing saved combos, combo notes, and backup format remain unchanged. Real-device/PWA installation testing has not been performed as part of this command audit.


Phase 28 — Mr.カラテ command audit (2026-11-16)
- Japanese CotW Wiki command table used as the primary character source.
- Confirmed move names and command directions are entered in numeric keypad notation.
- Dragon Howl/Dragon Dance timing descriptions retained; button timing icon details are marked for further verification.
- Saved combo data, notes, profile IDs, storage key, and backup schema are unchanged.
- Browser/device operation has not yet been tested.

Mr.カラテ Phase 28 R1 audit: https://w.atwiki.jp/cotw/pages/62.html (Japanese command table and image icons); SNK Japanese battle manual: https://www.snk-corp.co.jp/webmanual/fatalfury-cotw/battle/?lang=ja-JP.


Phase 28 R2 audit note (2026-11-16): 龍脚対応技の個別一覧を日本語Wikiの対応マーカーに基づいて明記。龍叫・龍舞は追加入力とタイミングの実機確認が未完了であることを明記。

Duck King Phase 29 reference: Japanese CotW Wiki roster and ChapaLog full command list (PS5 Arcade Style, published 2026-11-11). See COMMAND_AUDIT_DUCK_KING_PHASE29_20261116.txt.


Phase 29 R1 — Duck King command audit (2026-11-16)
- Standardized all Duck King command buttons to LP/LK/HP/HK notation and added three separately selectable REV Arts confirmed by the supplied command references and the official REV Arts rule.
- Reorganized Beat Rush branch entries to show their source move and state requirements; exact normal-version conditions remain marked as unverified where the practical test did not establish them.
- Resolved the move-name discrepancy by displaying タートルウォーク while documenting the alternate ダートルウォーク spelling in the audit notes.
- Added backstep, feint, and braking shared-system options. The universal step entry is included by the existing CotW migration; Duck King is classified as a Step character.
- Existing saved combos, combo notes, profile IDs, localStorage key, and JSON backup v3 remain protected.
- See COMMAND_AUDIT_DUCK_KING_PHASE29_R1_20261116.txt for command-by-command evidence and remaining verification items.


Phase 30: Kenshiro character data added. See COMMAND_AUDIT_KENSHIRO_PHASE30_20261116.txt.


Phase 31 — Kim Kaphwan
- Kim Kaphwan: 60 selectable entries (normal attacks, throws, dodge attacks, command combos, special moves, stance follow-ups, REV Arts, ground/air REV Blows, supers, potential supers, Hidden Gear, and shared systems). Command Combo I/II endings and some REV/feint details are explicitly marked for in-game verification where the source image notation is ambiguous.
- Profile ID cotw-kim-kaphwan is retained; existing saved combos and notes are preserved.
- Research: Japanese CotW Wiki Kim Kaphwan (updated 2026-11-10), Japanese CotW Wiki step/dash/backstep (updated 2026-11-03), and SNK official Japanese control guide.

- Draken (龍宮寺堅): 59 selectable entries (normal moves, throws, dodge attacks, unique command attacks, command combos, weak/strong/REV special moves, selectable follow-ups, REV Blows, supers, potential supers, Hidden Gear, and movement systems). No feint entry is included because Draken does not have a feint.


Phase 33 R2 — CotW共通システム拡張（2026-11-19）
- 共通システム欄にバックステップ、ノーマルジャンプ、ダッシュジャンプを追加。
- バックステップ: 地上で44または4+REV。ノーマルジャンプ: 7/8/9。ダッシュジャンプ: ステップ／ダッシュ中に9。
- 既存の同名共通システム項目は重複追加せず、既存の技データ・コマンド編集・メモ・保存コンボを上書きしない。
- 根拠: 日本語CotW Wiki「ステップ・ダッシュ・バックステップ」「初心者向け」、AppMedia「小ジャンプ・ダッシュジャンプの使い方」。

- Laocorn: 80 selectable entries covering normal attacks, throws, dodge attacks, Dark Cyclone Kick, command combos, Dark Barrier/Fist and follow-ups, Dark Jump routes, REV Blows, supers, Metal Laocorn transformation/form, Hidden Gear, and shared system actions. Command-image icons were individually checked against the Japanese Wiki; frame data was not invented.


Phase 34 — Laocorn (2026-11-20)
- Added 80 selectable entries for normal Laocorn and Metal Laocorn, including Dark Barrier, Dark Fist, Dark Jump branches, REV Blows, supers, transformation, and Hidden Gear.
- Added the current shared-system actions: ステップ/ダッシュ、バックステップ、ノーマルジャンプ、小ジャンプ、ダッシュジャンプ、前方投げ、後方投げ。
- Dark Blow and Dark Rising branch inputs, directional Dark Warp inputs, and Feint/Breaking markers were cross-checked against the individual command images on the Japanese CotW Wiki.
- Laocorn profile initialization only seeds a missing or empty move list. Existing non-empty move data, saved combos, notes, profile IDs, localStorage key, and JSON backup format are preserved.
- No real iPhone or Netlify runtime test was performed.
- Research: https://w.atwiki.jp/cotw/pages/89.html and SNK official Ver.3.4.1 patch notes: https://www.snk-corp.co.jp/official/fatalfury-cotw/patchnotes/v3.4.1/


Phase 36 - CotW Combination Attack Coverage (2026-11-20)
- Ensured selectable Combination Attack routes exist in every ready CotW character profile (20 profiles were missing them; 14 already had them).
- Four routes are available: standard (LP > HP > HP > HK), mid (LP > HP > HP > 6+HK), low (LP > HP > HP > 2+HK), and REV (LP > HP > HP > HK > HP+HK).
- Existing Hokutomaru routes are detected and retained without duplication.
- Migration is additive: it appends only missing routes and does not overwrite existing move entries, saved combos, notes, or backup data.
- The migration runs for existing profiles and newly initialized ready profiles.
- The full command audit is supplied separately and is not included in this deployment ZIP.


Phase 36（2026-11-21）:
- 共通システムのステップ／ダッシュ重複を統合。
- キャラクターの技備考にフェイント／ブレーキング対応が記録されている場合、共通システム欄の選択肢を補完。
- 共通システムのジャンプ・投げ項目の重複を統合。
- 最後に選択したキャラクターとメインタブを次回起動時に復元。
- 既存の保存コンボ、概要メモ、技データを保持する移行処理。

# ID-Group — Hamuga ID групп, байгууллагын бүртгэл

«Групп, байгууллагын бүртгэл» эпикийн (Hamuga ID, Critical) шаардлага, судалгаа болон цаашид гарах бичиг баримтууд.

## Бүтэц

```
docs/
├── requirements/
│   ├── backlog-mn.md            Эпикийн story-нуудын жагсаалт, эрэмбэ, хамаарал
│   ├── process-map-group-org-mn.md  Бүх үйлдлийн нэгдсэн процессын зураглал (Mermaid)
│   └── stories/                 Хэрэглэгчийн түүх + хүлээн авах шалгуур (NAV-024…NAV-032)
├── architecture/
│   └── spikes/                  Судалгаа
│       └── group-org-sso-research-mn.md   SSO дээрх групп, хүүхэд нэмэх, байгууллага баталгаажуулах
└── design/
    ├── ux-laws-review-NAV-024-mn.md   UX хуулиудаар (Laws of UX) үнэлж сайжруулсан тэмдэглэл
    └── prototypes/              Дарж үзэх HTML прототип (хөтөч дээр шууд нээнэ)
        └── NAV-024-groups.html            Миний групп: групп үүсгэх (4 төрөл), байгууллага бүртгэх, нэгдэх, админ
```

## Юунаас эхэлж унших вэ
1. [Судалгаа](docs/architecture/spikes/group-org-sso-research-mn.md): жишээ платформууд, Hamuga ID-ийн хүүхэд бүртгэх процесс, байгууллага баталгаажуулах аргууд.
2. [Процессын зураглал](docs/requirements/process-map-group-org-mn.md): бүх үйлдэл, ДАН-аар регистр/ТТД шалгах дараалал, төлвүүд.
3. [Backlog](docs/requirements/backlog-mn.md): story-нуудын жагсаалт ба хүргэх дараалал.
4. [Story-нууд](docs/requirements/stories/).

## Тэмдэглэл
- Story файлууд Nav Agile төслийн `docs/templates/user-story.md` загвартай. `decisions.md` (D-дугаартай PO-ийн шийдвэр) руу заасан холбоосууд Nav Agile repo-д байрладаг.
- Бүх story `draft` төлөвтэй: Hamuga-тай холбоотой ажлын босго (D38) — ICT Group-ийн бичгэн гэрээ байхаас өмнө `ready` болохгүй.

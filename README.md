# ID-Group — Hamuga ID групп, байгууллагын бүртгэл

«Групп, байгууллагын бүртгэл» эпикийн (Hamuga ID, Critical) шаардлага, судалгаа болон цаашид гарах бичиг баримтууд.

## Бүтэц

```
docs/
├── requirements/
│   ├── backlog-mn.md            Эпикийн story-нуудын жагсаалт, эрэмбэ, хамаарал
│   └── stories/                 Хэрэглэгчийн түүх + хүлээн авах шалгуур (NAV-024…NAV-032)
├── architecture/
│   └── spikes/                  Судалгаа
│       └── group-org-sso-research-mn.md   SSO дээрх групп, хүүхэд нэмэх, байгууллага баталгаажуулах
└── design/
    └── prototypes/              Дарж үзэх HTML прототип (хөтөч дээр шууд нээнэ)
        └── NAV-028-org-membership.html    Байгууллагад нэгдэх: урилга, ажлын имэйл, нэгдэх хүсэлт
```

## Юунаас эхэлж унших вэ
1. [Судалгаа](docs/architecture/spikes/group-org-sso-research-mn.md): жишээ платформууд, Hamuga ID-ийн хүүхэд бүртгэх процесс, байгууллага баталгаажуулах аргууд.
2. [Backlog](docs/requirements/backlog-mn.md): story-нуудын жагсаалт ба хүргэх дараалал.
3. [Story-нууд](docs/requirements/stories/).

## Тэмдэглэл
- Story файлууд Nav Agile төслийн `docs/templates/user-story.md` загвартай. `decisions.md` (D-дугаартай PO-ийн шийдвэр) руу заасан холбоосууд Nav Agile repo-д байрладаг.
- Бүх story `draft` төлөвтэй: Hamuga-тай холбоотой ажлын босго (D38) — ICT Group-ийн бичгэн гэрээ байхаас өмнө `ready` болохгүй.

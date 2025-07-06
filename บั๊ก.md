name: แจ้งปัญหา/บั๊ก
description: รายงานปัญหาที่พบในการใช้งานระบบ
title: "[Bug] "
labels: [bug]
assignees: ''

body:
  - type: markdown
    attributes:
      value: |
        ## ❗ รายละเอียดปัญหา

  - type: textarea
    id: what-happened
    attributes:
      label: สิ่งที่เกิดขึ้น
      placeholder: อธิบายว่าเกิดอะไรขึ้น
    validations:
      required: true

  - type: textarea
    id: steps
    attributes:
      label: ขั้นตอนที่ทำให้เกิดปัญหา
      placeholder: อธิบายขั้นตอนที่ทำให้เจอปัญหานี้
    validations:
      required: true

  - type: input
    id: environment
    attributes:
      label: อุปกรณ์ / เบราว์เซอร์ที่ใช้
      placeholder: เช่น iPhone 14 / Safari, Windows 11 / Chrome
    validations:
      required: true

  - type: textarea
    id: expected
    attributes:
      label: คาดว่าควรจะเกิดอะไร
      placeholder: ระบบควรทำงานแบบไหนตามที่ควรเป็น

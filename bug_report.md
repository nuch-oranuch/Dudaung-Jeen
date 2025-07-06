
name: Bug Report
description: รายงานปัญหาที่เกิดขึ้น
title: "[BUG] "
labels: [bug]
body:
  - type: textarea
    id: what-happened
    attributes:
      label: เกิดอะไรขึ้น?
      description: อธิบายสิ่งที่เกิดขึ้นและขั้นตอนการทำให้เกิด
      placeholder: รายละเอียดปัญหา
    validations:
      required: true

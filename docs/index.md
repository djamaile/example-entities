### Code example

```
interface IpsumDolor {
  lorem: string;
  amet: number;
  consectetur: boolean;
  adipiscing?: string[];
}

type SitAmet = 'lorem' | 'ipsum' | 'dolor' | 'sit' | 'amet';

enum ConsecteturEnum {
  Lorem = 'LOREM',
  Ipsum = 'IPSUM',
  Dolor = 'DOLOR',
}
```

### PlantUML

```plantuml
@startuml
title Login Sequence
    ComponentA->ComponentB: Login Request
    note right of ComponentB: ComponentB logs message
    ComponentB->ComponentA: Login Response
@enduml
```
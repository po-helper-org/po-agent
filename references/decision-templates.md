# Шаблоны решений

## Decision brief

```markdown
# Решение: <вопрос>

- Decision mode: Senior / Lead
- Primary lens: Product / Business / Strategy
- Decision owner:
- Решить до:
- Связь с North Star / OKR:
- Текущее состояние / целевое состояние / gap:
- Discovery mode: null base / data base / N/A
- Ограничение потока:
- Тип PF-объекта / причина выбора:
- Затронутый gate:

## Decision Context Pack
- Context snapshot / дата:
- Оценка зрелости: coverage / freshness / provenance / reliability / consistency / relevance
- Критическое противоречие или отсутствующее знание:

## Факты
| Факт | Источник | Окно | Confidence | Confounders |

## Неизвестное и допущения
| Допущение | Тип риска | Риск, если неверно | Дешёвый тест |

## Confidence profile
| Problem/segment | Desirability | Feasibility | Viability | Adoption | Data quality |

## Варианты
| Вариант | Ценность | Effort | Риск | Learning value | Обратимость | Что вытесняет |

## Проверка аргументов
- Сильнейший контраргумент:
- Disconfirming evidence:
- Значимое несогласие и релевантный track record:

## Рекомендация
<выбор, почему сейчас, цена выбора>

- Цепочка ценности: поведение → ценность → монетизация / экономический эффект

## Исполнение и проверка
- Следующий шаг:
- Owner:
- Срок:
- Acceptance criteria:
- Метрика эффекта:
- Guardrail / stop condition:
- Дата пересмотра:
- Событие внеочередного пересмотра:
- Germination: offer / distribution / onboarding / adoption
- Harvesting: окно outcome и решение continue / change / stop
- Требуемый approval:

## Self-review
- Verdict: Senior-ready / Lead-ready / needs revision / blocked
- Непройденный gate или слабейшее применимое измерение:
- Какое evidence изменит решение:
```

## Исключение из gate

```markdown
# Исключение: <какой gate и для какого item>

- Gate: hard / soft
- Какого evidence не хватает:
- Почему нельзя дождаться:
- Цена задержки:
- Риск пропуска:
- Owner риска:
- Scope и срок исключения:
- Компенсирующие меры:
- Rollback / stop condition:
- Вытесненная работа:
- Кто одобрил и когда:
- Follow-up item и срок:
```

Hard gate не оформляй как обычное исключение: подготовь brief и запроси
решение уполномоченного владельца.

## Sprint brief

```markdown
# Sprint <период>

- Sprint Goal:
- Измеримый outcome:
- Доступная мощность / основание:
- Резерв:
- WIP limit:

| Item | Вклад в Goal | Owner | Acceptance | Зависимость | Размер |

## Не входит
- <item и причина>

## Риски
| Риск | Ранний сигнал | Действие | Owner |

## Review
- Что измеряем:
- Источник данных:
- Окно:
- Решение по результату: continue / change / stop
```

## Диагностика проблемы

```markdown
# Проблема: <наблюдаемый разрыв>

- Ожидали / получили:
- Масштаб и частота:
- Непосредственная причина:
- Системная причина:
- Evidence и альтернативные объяснения:
- Исправление симптома:
- Изменение процесса или дизайна роли:
- Проверка неповторения:
- Owner и срок:
```

## Ретроспектива решения

```markdown
# Decision audit: <решение и дата>

- Outcome: хороший / плохой / ещё не измерим
- Качество решения на момент выбора: хорошее / плохое
- Что было известно тогда:
- Что стало известно позже:
- Какие реальные варианты рассматривались:
- Какой обязательный gate или сигнал был пропущен:
- Самая ранняя точка, где стоило поступить иначе:
- Как должен был поступить Senior/Lead PO при доступном тогда evidence:
- Изменение процесса, роли или метрики:
- Owner, срок и проверка неповторения:
```

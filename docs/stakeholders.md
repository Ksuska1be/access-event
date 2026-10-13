| Сущность | Атрибуты | Описание |
|----------|----------|----------|
| Event | id, title, date, location, description, is_inclusive | Мероприятие |
| Participant | id, name, email, phone, hearing_status | Участник |
| Organizer | id, name, contact, rating | Организатор |
| Registration | id, event_id, participant_id, status, created_at | Регистрация |
| Notification | id, event_id, type, message, color | Уведомление |
| Review | id, event_id, participant_id, rating, text | Отзыв |
| Category | id, name, description | Категория события |


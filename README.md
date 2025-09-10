select teacher_id, count(subject_id) as cnt
from teacher 
group by teacher_id
order by teacher_id asc;

Celery example
----------

**Run Server**

`celery -A download  worker --loglevel=info`

**Run the task**

`python3 -m download.send`

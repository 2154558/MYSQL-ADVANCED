# Antwoorden

1. Copy paste je gemaakte SQL query hieronder

SELECT * FROM game JOIN platform ON platform.id = game.platform_id;
   
2. Copy paste je gemaakte SQL query hieronder

SELECT * FROM game JOIN platform ON platform.id = game.platform_id WHERE game.id <= 10;
   
3. Copy paste je gemaakte SQL query hieronder
   
   SELECT name AND platform FROM game JOIN platform ON platform.id = game.platform_id;

4. Copy paste je gemaakte SQL query hieronder

SELECT game.name, platform.platform FROM game JOIN platform ON platform.id = game.platform_id WHERE game.name = "Call of Duty: Advanced Warfare";
   
5. Copy paste je gemaakte SQL query hieronder

SELECT game.name, platform.platform FROM game JOIN platform ON platform.id = game.platform_id WHERE game.name = "Borderlands" OR game.name = "Borderlands 2";
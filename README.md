**README**
**Overview**
This file contains sample user interaction data for a movie platform. Each row represents an interaction between a user and a movie, detailing the event type, device used, session details, and interaction duration. The data can be used for analysis to understand user behavior, movie engagement, and interaction trends.

**Data Columns**
1. interaction_id: Unique identifier for each user interaction.
2. user_id: Unique identifier for the user interacting with the platform.
3. movie_id: Unique identifier for the movie involved in the interaction.
4. interaction_type: Type of interaction (e.g., "click" or "view").
5. event_timestamp: Date and time when the interaction took place, in the format YYYY-MM-DD HH:MM:SS.
6. device_type: The type of device used for the interaction (e.g., "mobile", "tablet", "desktop").
7. session_id: Unique identifier for the session during which the interaction occurred.
8. duration_seconds: Duration of the interaction in seconds.

**Example Data**
interaction_id	user_id	movie_id	interaction_type	event_timestamp	device_type	session_id	duration_seconds
1	101	1001	click	2025-02-02 10:00:00	mobile	session_001	120
2	102	1002	view	2025-02-03 11:00:00	tablet	session_002	300
3	101	1001	click	2025-02-04 12:00:00	mobile	session_003	180
4	103	1003	view	2025-02-05 13:00:00	desktop	session_004	150
5	104	1004	click	2025-02-06 14:00:00	mobile	session_005	220

Invoke-RestMethod -Uri http://127.0.0.1:5000/predict -Method POST -Headers @{ "Content-Type" = "application/json" } -Body '{"league": "XX", "matches": [{"HomeTeam": "TeamA", "AwayTeam": "TeamB", "AvgH": 1.00, "AvgD": 1.00, "AvgA": 1.00, "AvgMORE25": 1.00, "AvgCLESS25": 1.00}]}'

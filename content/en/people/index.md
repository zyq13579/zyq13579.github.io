---
title: People

type: landing

sections:
  - block: people
    content:
      title: Meet the Team
      # Choose which groups/teams of users to display.
      #   Edit `user_groups` in each user's profile to add them to one or more of these groups.
      user_groups:
        - Principal Investigators
        - Graduate Students

      # sort_by: Params.last_name
      sort_by: Params.order_weight # 按此数字升序排列
      sort_ascending: true
    design:
      show_interests: false
      show_role: true
      show_social: true

  - block: markdown
    content:
      title: Undergraduate Students
      text: |
        - Name A, B.S., XX University (202x-202x)
        - Name B, B.S., XX University (202x-202x)

  - block: markdown
    content:
      title: Alumni
      text: |
        - Name A, M.S. (2025), current employment
        - Name B, M.S. (2025), current employment
---

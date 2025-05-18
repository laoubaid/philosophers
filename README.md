# 🍝 Dining Philosophers
  The Dining Philosophers Problem is a classic concurrency problem that involves philosophers sitting around a table with a bowl of spaghetti and one fork between each pair. Each philosopher alternates between thinking, eating, and sleeping. To eat, they need both the left and right forks. After eating, they release the forks, sleep, then think again. Philosophers don’t communicate and can't predict if others are starving. The goal is to ensure no philosopher starves, despite these constraints.

## 🧠 Summary

This project implements the classic **Dining Philosophers** problem using two approaches:

- 🧵 **Threads** (`dp_threads/`)
- 🔁 **Processes** (`dp_procs/`)

Learn the basics of **multithreading**, **process creation**, and **mutexes** for synchronization.

---

▶️ Usage
```bash
./philo number_of_philosophers time_to_die time_to_eat time_to_sleep [nb_times_each_philo_must_eat]
./philo 3 310 100 100 [2 (optional)]
```

🎓 42 School project

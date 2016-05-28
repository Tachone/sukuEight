add_executable(sukuEight_solver_basic server_basic.cc sudoku.cc eight.cc)
target_link_libraries(sukuEight_solver_basic muduo_net)

add_executable(sukuEight_solver_threadpool server_threadpool.cc sudoku.cc eight.cc)
target_link_libraries(sukuEight_solver_threadpool muduo_net)

add_executable(Eight_client_batch batch.cc sudoku.cc eight.cc)
target_link_libraries(Eight_client_batch muduo_net)

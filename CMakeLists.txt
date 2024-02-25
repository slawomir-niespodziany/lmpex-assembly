cmake_minimum_required(VERSION 3.22)

project (dispatcher VERSION 0.1 DESCRIPTION "LMP example app.")

add_subdirectory(lmp)

add_subdirectory(abstract_link)
add_subdirectory(eth_link)
add_subdirectory(gsm_link)
add_subdirectory(sat_link)

add_subdirectory(broker)

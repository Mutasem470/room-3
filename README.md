Split sensor data into two sets manually. Use a 60-40 ratio.

This code calculates a 60% split index, partitions the data into two sets, and prints them.


# room-3
 Train-Test // Split From Scratch Split sensor data into two sets manually. 
data = [2.3, 3.1, 4.5, 5.6, 7.2]

# Calculate the index for the 60% split
size_60 = int(0.6 * len(data))

# Split the data into two sets
data_60 = data[:size_60]
data_40 = data[size_60:]

# Print the results
print(f"Data_60: {data_60}")
print(f"Data_40: {data_40}")

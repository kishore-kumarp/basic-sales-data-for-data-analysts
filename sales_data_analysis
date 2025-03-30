import pandas as pd

def load_data(file_path):
    """Load data from a CSV file."""
    data = pd.read_csv(file_path)
    return data

def calculate_total_sales(data):
    """Calculate the total sales."""
    total_sales = data['Sales'].sum()
    return total_sales

def calculate_average_sales(data):
    """Calculate the average sales."""
    average_sales = data['Sales'].mean()
    return average_sales

def main():
    # Load the sales data
    file_path = 'sales_data.csv'  # Replace with the path to your CSV file
    data = load_data(file_path)
    
    # Calculate total and average sales
    total_sales = calculate_total_sales(data)
    average_sales = calculate_average_sales(data)
    
    # Display the results
    print(f"Total Sales: ${total_sales:.2f}")
    print(f"Average Sales: ${average_sales:.2f}")

if __name__ == "__main__":
    main()

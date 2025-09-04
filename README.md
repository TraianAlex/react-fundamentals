React Fundamentals

npm run dev

## Download Microsoft package signing key and add the repository
wget https://packages.microsoft.com/config/ubuntu/24.04/packages-microsoft-prod.deb -O packages-microsoft-prod.deb

sudo dpkg -i packages-microsoft-prod.deb

rm packages-microsoft-prod.deb

## Update package index and install .NET 8 SDK
sudo apt update

sudo apt install -y dotnet-sdk-8.0

dotnet --version

cd HouseApi

dotnet run

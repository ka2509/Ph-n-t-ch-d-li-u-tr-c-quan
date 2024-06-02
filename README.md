# Dự án Phân tích Sản lượng Lúa và Điều kiện Khí tượng

## Mô tả dự án

Dự án này nhằm thu thập, xử lý và phân tích dữ liệu về sản lượng, diện tích, năng suất lúa của các tỉnh thuộc Việt Nam, kết hợp với dữ liệu khí tượng từ các trạm đo để phân tích mối quan hệ giữa điều kiện khí tượng và sản lượng lúa. Dữ liệu về lúa được lấy từ website của Tổng cục Thống kê Việt Nam, và dữ liệu khí tượng được lấy từ trang web Copernicus Climate Data Store (CDS).

## Các bước thực hiện

### 1. Thu thập dữ liệu

#### Dữ liệu về lúa

Dữ liệu về sản lượng, diện tích, năng suất lúa của các tỉnh thuộc Việt Nam được lấy từ website Tổng cục Thống kê Việt Nam:

- Website: [Tổng cục Thống kê Việt Nam](https://www.gso.gov.vn/)

#### Dữ liệu khí tượng

Dữ liệu khí tượng được thu thập từ các trạm đo và tải về từ trang web Copernicus Climate Data Store (CDS) dưới định dạng NetCDF-3:

- Dataset: [Reanalysis ERA5-Land](https://cds.climate.copernicus.eu/cdsapp#!/dataset/reanalysis-era5-land?tab=overview)

### 2. Xử lý dữ liệu

#### Dữ liệu về lúa

Dữ liệu được xử lý và biểu diễn dưới dạng các biểu đồ để dễ dàng phân tích.

#### Dữ liệu khí tượng

Dữ liệu khí tượng được tải về dưới định dạng NetCDF-3 và chuyển thành DataFrame sử dụng thư viện Python để xử lý.

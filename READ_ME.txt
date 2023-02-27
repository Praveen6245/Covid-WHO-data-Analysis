1) 	Dataset summary:
		Name of the sheet: Global cases(1128*237=267337 records)
		Samples: 237 countries data is collected
		Regions: 237 countries are classified into 7 regions. # Use categorical Index
		Details: This sheet contains the details of cases and reported from "03-01-2020" to "02-02-2023"(date of extracting the report) i.e,1127 days from all the available countries.Below are the column's definitions:
			Date_reported: Date of reporting to WHO
			Country_code: ISO Alpha-2 country code
			Country: Country, territory, area
			WHO_region: Six WHO regions- Regional Office for Africa (AFRO), Regional Office for the Americas (AMRO), Regional Office for South-East Asia (SEARO), Regional Office for Europe (EURO), Regional Office for the Eastern Mediterranean (EMRO), and Regional Office for the Western Pacific (WPRO).
			New_cases: New confirmed cases. Calculated by subtracting previous cumulative case count from current cumulative cases count.
			Cumulative_cases: Cumulative confirmed cases reported to WHO to date.
			New_deaths: New confirmed deaths. Calculated by subtracting previous cumulative deaths from current cumulative deaths.
			Cumulative_deaths: Cumulative confirmed deaths reported to WHO to date.
2) Dataset summary:
		Name of the sheet: Global vaccination (230 records)
		Samples: 230 countries data is collected
		Details: These are the column's definitions:
			ISO3: ISO Alpha-3 country code
			WHO_REGION: WHO regions
			DATA_SOURCE: REPORTING - Data reported by Member States(REPORTING) or from official reports (OWID - Our World in Data)
			DATE_UPDATED: Date of last update
			TOTAL_VACCINATIONS: Cumulative total vaccine doses administered
			PERSONS_VACCINATED_1PLUS_DOSE: Cumulative number of persons vaccinated with at least one dose
			TOTAL_VACCINATIONS_PER100: Cumulative total vaccine doses administered per 100 population
			PERSONS_VACCINATED_1PLUS_DOSE_PER100: Cumulative persons vaccinated with at least one dose per 100 population
			PERSONS_FULLY_VACCINATED: Cumulative number of persons fully vaccinated
			PERSONS_FULLY_VACCINATED_PER100: Cumulative number of persons fully vaccinated per 100 population
			VACCINES_USED: Combined short name of vaccine: “Company - Product name” (see below)
			FIRST_VACCINE_DATE: Date of first vaccinations. Equivalent to start/launch date of the first vaccine administered in a country.
			NUMBER_VACCINES_TYPES_USED: Number of vaccine types used per country, territory, area
			PERSONS_BOOSTER_ADD_DOSE: Persons received booster or additional dose
			PERSONS_BOOSTER_ADD_DOSE_PER100: Persons received booster or additional dose per 100 population

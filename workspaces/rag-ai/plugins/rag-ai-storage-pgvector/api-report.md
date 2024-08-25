## API Report File for "@alithya-oss/plugin-rag-ai-storage-pgvector"

> Do not edit this file. It is a report generated by [API Extractor](https://api-extractor.com/).

```ts
import { DatabaseService } from '@backstage/backend-plugin-api';
import { LoggerService } from '@backstage/backend-plugin-api';
import { RoadieVectorStore } from '@alithya-oss/plugin-rag-ai-node';
import { RootConfigService } from '@backstage/backend-plugin-api';

// @public (undocumented)
export function createRoadiePgVectorStore({
  logger,
  database,
  config,
}: PgVectorStoreInitConfig): Promise<RoadieVectorStore>;

// @public (undocumented)
export interface PgVectorStoreInitConfig {
  // (undocumented)
  config: RootConfigService;
  // (undocumented)
  database: DatabaseService;
  // (undocumented)
  logger: LoggerService;
}

// @public
export interface RoadiePgVectorStoreOptions {
  // (undocumented)
  amount?: number;
  // (undocumented)
  chunkSize?: number;
}

// (No @packageDocumentation comment for this package)
```
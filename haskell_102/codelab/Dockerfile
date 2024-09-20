# Using haskell:8 instead of latest due to deprecation warning
# on cabal
FROM haskell:8
WORKDIR /app

# Install Stack
RUN apt-get update && apt-get install -y curl
RUN curl -sSL https://get.haskellstack.org/ | sh

# Copy all source files into container
COPY . .

FROM mongo:3.6

ENV AUTO_RUN_DIR="/docker-entrypoint-initdb.d" \
    INSTALL_MONGO_SHELL="setup.sh"

COPY ./$INSTALL_MONGO_SHELL $AUTO_RUN_DIR/

RUN chmod +x $AUTO_RUN_DIR/$INSTALL_MONGO_SHELL
